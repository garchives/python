# Python list 数据类型

## 实现原理

## 示例演示

new_capacity = new_size + new_size >> 3 + new_size < 9 ? 3 : 6

---

lst = [] => []

--

lst.append(11)

new_size => 1 => new_capacity = 1 + 0 + 3 = 4 => [ [11] [22] [33] [44] ]

---

sleep(100000)

lst.append(55)

new_size => 5 => new_capacity = 5 + 0 + 3 =08 => [ [11] [22] [33] [44]  [55] [66] [77] [88]  ]

new_size => 9 => new_capacity = 9 + 1 + 6 = 16  => [ [11] [22] [33] [44]  [55] [66] [77] [] [] [] [] [] []....      ]

---

new_size = 7 => new_capacity = 7 + 0 + 3 = 10 => []
