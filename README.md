# POSITION

### absolute
- Chỉ chạy đc khi cha của nó có position là relative
- Không cho cha width và height nếu cha không set width, height

### relative
- Nếu không có float -> sẽ hiển thị như block (width = 100%)

### fixed
- Vị trí cố định theo screen màn hình

# DISPLAY

### inline-block
- Phải có width và height
- Lý do: set `text-align:center;` dễ hơn `position:relative; float:left;`

# Padding
- Vẫn thuộc cha -> sẽ apply các thuộc tính của cha như background...
- Hiệu lực so với cha
- Khi đi với `box-sizing:border-box;` thì width, height sẽ trừ đi thay vì cộng (default) <- cơ chế của Bootstrap, mục đích để không ảnh hưởng Grid System

# Margin
- Hiệu lực so với các div (nội dung) kế bên (neighbour)
- Không dùng được với `box-sizing`
