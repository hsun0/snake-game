# Snake Game
中山大學物件導向程式設計作業。

貪食蛇遊戲，支援多種自動遊玩策略、障礙物與強化學習訓練。

## 組員
- B123040045 林柏儒
- B123040048 吳紹彰
- B123040053 張承勛

## 執行方式

需安裝 Python 3.10 以上版本與 uv。

```bash
uv sync
uv run main_snake.py --render
```

加入障礙物：

```bash
uv run main_snake.py --render --obstacles
```

## 訓練模型

```bash
uv run main_snake.py --mode train --episodes 1000
```