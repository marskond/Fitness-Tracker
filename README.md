# Fitness-Tracker
Описание проекта:
Фитнес трекер будет позволять пользователям вводить информацию о своих тренировках, поможет отслеживать прогресс и достижение целей.
Реализуемый функционал:
-Ввод данных о тренировках (тип упражнения, длительность, пройденное расстояние и сожжённые калории)
-Хранение и управление историей тренировок
-Анализ данных (графики, статистика)
-Установка и отслеживание целей 
Экспорт данных в файл (CSV, JSON)
Архитектура:
Классы:
1. Workout
Атрибуты: exercise_type, duration, distance, calories_burned, date
Методы: calculate_calories(), display_info()
2. User
Атрибуты: name, age, weight, workouts
Методы: add_workout(), get_total_calories(), set_goal()
3. Tracker
Атрибуты: user, workouts_log
Методы: record_workout(), generate_report(), display_progress()
4. DataManager
Атрибуты: file_path
Методы: save_to_file(), load_from_file()
Эта структура позволит делиться функционалом и данными между классами, создавая удобный и расширяемый проект.
