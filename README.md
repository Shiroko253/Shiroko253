# 3 2 1 2 3

## Me?
---
- 一個特立獨行的存在 也是一個神秘的存在
  - 所有的資料庫並不包含他的訊息
  - Miya253又稱Shiroko
- 一個可以説是怪人 有可以説是 維護者

[@xuemeng1987](https://github.com/xuemeng1987)
- 零號計劃發起者

[@Miya253](https://github.com/Miya253)
- 零號計劃參與者兼bug尋找員
---

## From?

---

- Malaysia
  - Sarawak
  - Kota Padawan

---

## How Old?

---

- 19 (19-7-2005)

---

## 你想看什麽

---

你還想看到什麽

我變成寶可夢嗎


---

## progem a project

- [零號計劃](https://github.com/xuemeng1987/Yuyuko_Bot)
   - python
- [個人網頁web](https://xuemeng1987.github.io/ShirokoHub/)
  - 使用的語言
  - html
  - css
- [零號計劃的Discord機器人](https://discord.com/oauth2/authorize?client_id=852046004550238258&permissions=15&scope=bot)
  - 使用語言
  - cn-zh

---

## Fine This is you'r lat's time now

- [osu.ppy](https://osu.ppy.sh/users/23623263)
- [Discord](https://discord.gg/4GE3FpR8rH)
- **X** (原 Twitter): [@yuemeng62](https://x.com/yuemeng200)
- **Discord**: miya253 （顯示名稱：Shiroko）
- **GitHub**: [Miya253](https://github.com/xuemeng1987)
- **Instagram**: [Miya_2530_](https://www.instagram.com/miya_2530_/)

---

## ...

[@Miya253](https://github.com/Miya253)

```python
import tkinter as tk
from tkinter import messagebox
import time

root = tk.Tk()
root.title("System Shutdown")
root.geometry("400x300")
root.configure(bg="black")

root.attributes("-fullscreen", True)

countdown_label = tk.Label(root, text="", font=("Helvetica", 48, "bold"), fg="red", bg="black")
countdown_label.pack(expand=True)

def fake_shutdown():
    for i in range(10, -1, -1):
        countdown_label.config(text=f"Shutting down in {i} seconds...")
        root.update()
        time.sleep(1)

    messagebox.showinfo("Shutdown", "System shutdown completed.")
    root.destroy()
def blue_screen_of_death():
    root.configure(bg="blue")
    countdown_label.config(fg="white", text="A critical error has occurred.")
    root.update()
    time.sleep(3)
    fake_shutdown()

blue_screen_of_death()
root.mainloop()
```
