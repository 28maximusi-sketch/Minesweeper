# Minesweeper – 7 Languages

Классическая игра «Сапёр» (Minesweeper) на 7 языках программирования. Каждая версия поддерживает:

- **Разные уровни сложности** (9x9/10 мин, 16x16/40 мин, 24x24/99 мин)
- **Левый клик** – открыть клетку
- **Правый клик** – поставить/убрать флаг
- **Рекурсивное открытие** пустых областей
- **Таймер** (секундомер с начала игры)
- **Счётчик оставшихся мин**
- **Первый клик никогда не попадает в мину**
- **Защита от случайного открытия мины при первом ходе**
- **Хранение рекордов** (лучшее время для каждого уровня)

## Реализации

| Язык | Технология | Особенности |
|------|------------|-------------|
| Python | Tkinter / Pygame | Классический GUI |
| Go | Ebitengine | Графика, производительность |
| Rust | ggez / SDL2 | Высокая скорость |
| C# | Windows Forms | Родной Windows-интерфейс |
| JavaScript | HTML5 Canvas + Web Audio | Браузерная версия |
| TypeScript | Canvas + классы | Аналогично JS с типами |
| Java | Swing | Кроссплатформенный GUI |

## Запуск

### Python
```bash
cd python
pip install pygame  # или используйте tkinter (встроен)
python minesweeper.py
cd go
go mod tidy
go run minesweeper.go
cd go
go mod tidy
go run minesweeper.go
cd rust
cargo run
cd csharp
dotnet run
cd ts
npm install
npx webpack
open index.html
cd java
javac Minesweeper.java
java Minesweeper
+-------------------+
|  💣 010  ⏱️ 00:12  |
+-------------------+
|  ?  ?  1  1  .    |
|  1  2  ?  .  .    |
|  .  .  .  .  .    |
+-------------------+
