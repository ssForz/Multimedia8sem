# Результаты обучения моделей в лабораторных работах 6-8
## Лабораторная работа №6
| Задача  | Модель |  Обычная  | Улучшенный бейзлайн |
|-------|-----|-------|-----|
| Классификация | ResNet18  | acc: 0.82, f1-score: 0.83, recall: 0.83, precision: 0.84 | acc: 0.91, f1-score: 0.71, recall: 0.71, precision: 0.77 |
|    | ViT  | acc: 0.38, f1-score: 0.31, recall: 0.39, precision: 0.32 | - |
|    | Собственная имплементация  | acc: 0.62, f1-score: 0.6, recall: 0.62, precision: 0.66 | acc: 0.65, f1-score: 0.49, recall: 0.51, precision: 0.59 |

## Лабораторная работа №7 
| Задача  | Модель |  Обычная  | Улучшенный бейзлайн |
|-------|-----|-------|-----|
| Сегментация | UNet  | acc: 0.9538, loss: 0.144, dice: 0.846, IoU: 0.7378 | acc: 0.9572, loss: 0.142, dice: 0.885, IoU: 0.796 |
|    | Собственная имплементация  | acc:  0.88, loss: 0.83, dice: 0.553 , IoU: 0.39 | acc: 0.81, loss: 0.528, dice: 0.548, IoU: 0.382 |

## Лабораторная работа №8
| Задача  | Модель |  Обычная  | Улучшенный бейзлайн |
|-------|-----|-------|-----|
| Обнаружение | yolov8  | acc: 0.8397, precision: 0.6547, recall:0.7900, IoU: 0.6537 | acc: 0.8397, precision: 0.2453, recall:0.7012, IoU: 0.2441 |
