#!/bin/bash

# Исходная директория
SOURCE_DIR="/mnt/d/IPHONEBACKUP"

# Целевая директория
DEST_DIR="/mnt/d/final"

# Создаем целевую директорию, если она не существует
mkdir -p "$DEST_DIR"

# Переносим медиафайлы (изображения и видео) в одну директорию
find "$SOURCE_DIR" -type f \( -iname "*.jpg" -o -iname "*.jpeg" -o -iname "*.png" -o -iname "*.mp4" -o -iname "*.mov" \) -exec mv {} "$DEST_DIR" \;

echo "Перенос завершен!"
