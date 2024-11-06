## css flex

```scss
flex: 0 0 auto;
flex: 0 0 100%;
display: flex;
gap: 1rem;
flex-wrap: wrap;
flex-flow: row wrap;
flex-direction: column;
justify-content: space-between;
```

## css grid

```scss
display: grid;
grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); /* 250px = ขนาดของ card ภายใน*/
gap: 0.5rem;
grid-template-areas:
      "col  . "
      "col  col"
      "col-1  col-2"
grid-template-columns: 1fr 1fr;
grid-area: col-1;
```

---

## scss

```scss
overflow: auto /* แสดงผลอัตโนมัติ ถ้าข้อมูลเกินก็จะมีแถบ scroll bar ขึ้นให้ */

margin: 0 auto; /* จัดกึ่งกลาง */
padding: 1 2 3 4; /* 1:บน 2:ขวา 3:ล่าง 4:ซ้าย */
display: none;
position: relative;
position: absolute;
box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
border: 2px solid rgba(120, 120, 120, 0.4);
border-radius: 10px;
outline: auto;

align-items: center;
justify-content: center;
text-align: center; /* ตัวอักษรอยู่ตรงกลาง */
white-space: nowrap; /* ไม่ให้ข้อความที่เว้นวรรค มีการเว้นบรรทัด (Responsive) */
list-style: none;
text-decoration: none;
cursor: pointer;
```

---