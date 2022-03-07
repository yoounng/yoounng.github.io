https://python3-cookbook.readthedocs.io/zh_CN/latest/c14/p07_catching_all_exceptions.html   捕获所有异常

# win32gui

win32gui.PostMessage(hwnd, win32con.WM_CLOSE, 0, 0)

关闭窗口


# 离奇bug

csv等文件中，strip()只能去除前端，无法去除后端，可能是因为后端有换行符……建议先strip("\n")