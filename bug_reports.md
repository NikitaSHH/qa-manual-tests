### Bug #1 — [Signup] Нет сообщения об ошибке при пустом пароле

**Environment:**
- URL: https://www.demoblaze.com/
- OS: Windows 10
- Browser: Chrome 116

**Steps to reproduce:**
1. Перейти на https://www.demoblaze.com/
2. Нажать "Signup"
3. Ввести username
4. Оставить поле password пустым
5. Нажать "Signup"

**Actual result:** страница обновляется, ошибки нет  
**Expected result:** появляется сообщение "Password cannot be empty"  

**Severity:** Major  
**Priority:** High  

---

### Bug #2 — [Login] Ошибка при неверном пароле

**Environment:**
- URL: https://www.demoblaze.com/
- OS: Windows 10
- Browser: Chrome 116

**Steps to reproduce:**
1. Перейти на сайт
2. Нажать "Login"
3. Ввести валидный username и неверный пароль
4. Нажать "Login"

**Actual result:** появляется ошибка 500  
**Expected result:** сообщение "Invalid credentials"  

**Severity:** Major  
**Priority:** High
