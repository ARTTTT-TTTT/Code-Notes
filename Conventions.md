# Conventions

## File and Folder Naming

| **Folder Type** | **Naming Convention**       | **Example**                                |
| --------------- | --------------------------- | ------------------------------------------ |
| **api**         | camelCase                   | `user.js`, `data.js`                       |
| **assets**      | lowercase_with_hyphens      | `image-1.jpg`, `logo.png`                  |
| **components**  | PascalCase (UpperCamelCase) | `Header.jsx`, `Footer.jsx`                 |
| **constants**   | UPPERCASE_WITH_UNDERSCORES  | `API_URL.js`, `MAX_LIMIT.js`               |
| **functions**   | camelCase                   | `calculateTotal.js`, `submitForm.js`       |
| **lib**         | camelCase                   | `utility.js`, `helper.js`                  |
| **middleware**  | camelCase                   | `authMiddleware.js`, `loggerMiddleware.js` |
| **models**      | PascalCase (UpperCamelCase) | `UserModel.js`, `ProductModel.js`          |
| **mocks**       | camelCase                   | `userMock.js`, `productMock.js`            |
| **pages**       | lowercase with hyphens      | `index.jsx`, `contact-us.jsx`              |
| **routes**      | camelCase                   | `userRoute.js`, `authRoute.js`             |
| **services**    | camelCase                   | `userService.js`, `emailService.js`        |
| **styles**      | camelCase                   | `mainStyles.css`, `theme.css`              |
| **tests**       | PascalCase (UpperCamelCase) | `User.test.js`, `App.test.js`              |

## Function Naming

| **Function Type**        | **Naming Convention**       | **Example**                        |
| ------------------------ | --------------------------- | ---------------------------------- |
| **Pages Functions**      | PascalCase (UpperCamelCase) | `IndexPage()`, `AboutPage()`       |
| **API Functions**        | camelCase                   | `getUserData()`, `fetchData()`     |
| **Components Functions** | camelCase                   | `handleClick()`, `updateState()`   |
| **Other Functions**      | camelCase                   | `calculateTotal()`, `submitForm()` |

## Variable Naming

| **Variable Type**      | **Naming Convention**      | **Example**                    |
| ---------------------- | -------------------------- | ------------------------------ |
| **Arrays**             | camelCase + plural         | `userList`, `productItems`     |
| **Boolean Variables**  | is/has + camelCase         | `isActive`, `hasPermission`    |
| **Constants**          | UPPERCASE_WITH_UNDERSCORES | `API_URL`, `BASE_URL`          |
| **Function Arguments** | camelCase                  | `userData`, `callbackFunction` |
| **Global Variables**   | UPPERCASE_WITH_UNDERSCORES | `MAX_COUNT`, `API_KEY`         |
| **Local Variables**    | camelCase                  | `userData`, `totalAmount`      |
| **Objects**            | camelCase                  | `userInfo`, `productDetails`   |

---
