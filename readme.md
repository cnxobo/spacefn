SpaceFn 是一种键盘改良布局方案，其核心思想是把空格键作为自定义的Fn键使用,比如把 Space + 1 映射为F1, Space + e 映射为Esc, Space + j映射为方向键下,极大的减少了手指的移动,提高键盘使用效率.

该布局带来的缺点是: 空格键只有释放时才生效,长按空格时不能持续输出空格; 偶尔会遇到空格没释放就点下一字母,导致不生效或者误触热键.

缺点1,通过映射 Space+b 热键实现持续的输出空格

缺点2,需要刻意的自我训练快速释放空格键.

本方案是通过AutoHotKey实现的, 
映射:

Space + 1~0,-= -> F1~12

Space + e -> Esc

Space + b -> Space

Space + hjkl -> Vim-like 方向键 ←↓↑→