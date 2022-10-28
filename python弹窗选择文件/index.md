# Python弹窗选择文件

首先需要引入2个包：

```
import tkinter as tk
from tkinter import filedialog
```

然后然后实例化 tkinter

```
    root = tk.Tk()
    root.withdraw()
```

获取选取的文件

```
   f_path = filedialog**.askopenfilename()
    print('\n获取的文件地址：', f_path)**
```

