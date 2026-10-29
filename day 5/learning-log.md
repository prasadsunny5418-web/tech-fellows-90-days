# Student Registration Demo — Learning Log

## 1. What I Built
I built a student registration form using HTML. It includes name, email, age, course, study mode, learning goals, and a practice-data confirmation checkbox.

## 2. Validation Checks Tested
- Required fields: The browser showed a validation message when I submitted the empty form.
- Email validation: The browser rejected an invalid email address.

## 3. One Bug I Fixed
I broke the email label connection by changing its `for` attribute. The label stopped focusing the email input. I fixed it by matching `for="email"` with `id="email"`.

## 4. Why Client-Side Validation Is Not Enough
Client-side validation can be bypassed. A real application must also validate data on the server to protect against invalid or harmful input.

## 5. One Improvement for Later
I will add CSS to make the registration form more attractive and mobile-friendly.