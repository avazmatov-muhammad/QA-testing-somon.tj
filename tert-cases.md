# Test Cases — Somon.tj

## TC-01 Login with valid data
Steps:
1. Open login page
2. Enter valid email
3. Enter valid password
4. Click Login

Expected: User is logged in

---

## TC-02 Login with invalid password
Steps:
1. Enter valid email
2. Enter wrong password
3. Click Login

Expected: Error message

---

## TC-03 Search functionality
Steps:
1. Go to homepage
2. Enter search keyword
3. Click search

Expected: Relevant results

---

## TC-04 Create ad
Steps:
1. Login
2. Click “Create Ad”
3. Fill form
4. Submit

Expected: Ad is created

---

## TC-05 Empty fields validation
Steps:
1. Open form
2. Leave fields empty
3. Submit

Expected: Validation error

---

## TC-06 Boundary Value (BVA)
Input field limit 1–100 characters:
- 0 → error
- 1 → success
- 100 → success
- 101 → error
