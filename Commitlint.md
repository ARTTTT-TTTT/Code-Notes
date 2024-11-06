# Commit Type Descriptions

| **Commit Type** | **Description**                                                                                           | **Example**                            |
| --------------- | --------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| **feat**        | เพิ่มฟีเจอร์ใหม่ในแอปพลิเคชัน                                                                             | `feat: add user login functionality`   |
| **fix**         | แก้ไขข้อบกพร่องในแอปพลิเคชัน                                                                              | `fix: correct user authentication bug` |
| **docs**        | ปรับปรุงเอกสาร (เช่น README, comments)                                                                    | `docs: update installation guide`      |
| **chore**       | การเปลี่ยนแปลงที่ไม่เกี่ยวข้องกับฟังก์ชันการทำงาน (เช่น การตั้งค่า, การอัปเดต dependencies)               | `chore: update project dependencies`   |
| **style**       | การปรับรูปแบบของโค้ด เช่น การจัดระเบียบ, การตั้งค่าเครื่องหมายวรรคตอน โดยไม่ส่งผลกระทบต่อฟังก์ชันการทำงาน | `style: format code with prettier`     |
| **refactor**    | การเปลี่ยนแปลงโค้ดที่ทำให้โค้ดมีความสะอาดและมีประสิทธิภาพขึ้น โดยไม่เปลี่ยนแปลงพฤติกรรมของโปรแกรม         | `refactor: simplify login function`    |
| **ci**          | การปรับเปลี่ยนการตั้งค่า CI (Continuous Integration)                                                      | `ci: update GitHub Actions workflow`   |
| **test**        | การเพิ่มหรือแก้ไข test cases                                                                              | `test: add unit tests for login`       |
| **perf**        | การปรับปรุงประสิทธิภาพของแอปพลิเคชัน                                                                      | `perf: optimize login function`        |
| **revert**      | การย้อนกลับการเปลี่ยนแปลงใน commit ที่ผ่านมา                                                              | `revert: undo changes to login form`   |
| **vercel**      | ใช้เฉพาะเมื่อการเปลี่ยนแปลงเกี่ยวข้องกับการใช้งาน Vercel (เช่น การตั้งค่า, Deployment)                    | `vercel: update deployment config`     |

---

## commitlint.config.js

```js

module.exports = {
  extends: ['@commitlint/config-conventional'],
  rules: {
    //   TODO Add Scope Enum Here
    // 'scope-enum': [2, 'always', ['yourscope', 'yourscope']],
    'type-enum': [
      2,
      'always',
      [
        'feat',
        'fix',
        'docs',
        'chore',
        'style',
        'refactor',
        'ci',
        'test',
        'perf',
        'revert',
        'vercel',
      ],
    ],
  },
};

```

---