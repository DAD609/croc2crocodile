# croc2crocodile
## Цели проекта
Проект **croc2crocodile** позволяет дообучать модель MT5 (small) из библиотеки Hugging Face. Основная задача — улучшить качество текста, включая:
- исправление грамматических ошибок и пунктуации;
- повышение стилевой корректности;
- улучшение информативности текста;
- устранение избыточности в формулировках;
- обеспечение консистентности терминологии.

Чтобы добиться стабильных и достоверных результатов от модели, рекомендуется создать обширный и качественный датасет, состоящий из пар "плохих/хороших" документов. Важно, чтобы исправления в "хороших" документах обучающей выборки соответствовали общим структурам и специфике сферы деятельности.
 Среднее время обучения на GPU T4 в 10 эпох равно ~10 мин.

## Установка
Вы можете установить и запустить проект, следуя инструкциям:
```bash
git clone https://github.com/DAD609/croc2crocodile.git
cd croc2crocodile
pip install -r requirements.txt
```
