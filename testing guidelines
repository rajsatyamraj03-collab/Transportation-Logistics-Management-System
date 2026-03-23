# Testing & Pull Request Validation Guidelines

This document defines the testing standards and pull request validation requirements
for the Transportation-and-Logistics MERN project.

---

## Project Structure Overview

Backend:
- controllers/
- routes/
- models/
- services/
- middlewares/

Frontend:
- src/
- public/

---

## 1. Backend Testing Guidelines

When modifying backend code:

- Test all affected API routes manually using:
  - Postman
  - Thunder Client

Ensure:

- Correct HTTP status codes (200, 201, 400, 401, 404, 500)
- Proper JSON response structure
- Validation errors handled properly
- Middleware (auth, validation) works correctly
- Database operations (create, update, delete) function as expected

If adding new routes:
- Verify route is properly registered in `routes/`
- Ensure controller logic is clean and error-handled
- Avoid exposing sensitive data

---

## 2. Frontend Testing Guidelines

When modifying frontend (inside `src/`):

- Ensure UI renders without console errors
- Forms validate inputs properly
- API calls are correctly connected
- Responsive design works on different screen sizes
- No broken navigation links

After changes:

- Run the frontend locally
- Check browser console for errors
- Verify integration with backend

---

## 3. Manual Testing Checklist (Before PR)

Before submitting a Pull Request, confirm:

- [ ] Application runs locally (frontend & backend)
- [ ] No console errors in browser
- [ ] No server crashes
- [ ] Existing features are not broken
- [ ] New feature works as expected
- [ ] No sensitive data committed
- [ ] Code follows project folder structure

---

## 4. Pull Request Requirements

All PRs must:

- Have a clear and descriptive title
- Reference the related issue (e.g., Fixes #34)
- Include a short description of changes
- Be tested locally before submission
- Not include unnecessary files (node_modules, .env, build files)
- Follow existing naming conventions

---

## 5. Code Quality Standards

- Maintain consistent indentation
- Remove unused imports and variables
- Avoid commented-out code
- Keep functions small and readable
- Handle errors properly using try-catch (backend)

---

Following these guidelines ensures maintainability, stability, and high-quality contributions.
