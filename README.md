# Выполнено Ямалетдиновой И. И., гр. 432Б

### Ход работы:
1. Установил Docker Desktop. Создал папку lab1. В нее поместил файлы app.py и requirements.txt с GitHub.

   <img width="516" height="355" alt="image" src="https://github.com/user-attachments/assets/64a705e2-50f6-4a43-b506-eef9c975b944" />

2. В этой же папке создал Dockerfile. Учтен проброс порта 1234.

   <img width="1052" height="91" alt="image" src="https://github.com/user-attachments/assets/afd63830-5cae-47f5-8017-76177de51d9a" />

3. В Docker Desktop собрал образ с помощью `docker build -t my-image .`

   <img width="989" height="266" alt="image" src="https://github.com/user-attachments/assets/71f78941-1232-42bf-9b32-f169cf244ad3" />

4. Далее запустил контейнер `docker run -p 1234:1234 my-image`
   
   <img width="928" height="523" alt="image" src="https://github.com/user-attachments/assets/c3ab517b-15d0-4a8b-af61-5ec18fee32d3" />

5. При переходе по ссылке `http://localhost:1234/`:

   <img width="928" height="523" alt="image" src="https://github.com/user-attachments/assets/b473faee-7637-4a0d-af68-9df61ce3e8da" />

6. Далее создан файл docker-compose.yml:

   <img width="555" height="918" alt="image" src="https://github.com/user-attachments/assets/24bd2b1f-e697-41d9-b56a-6108fcf49ca3" />


7. Пересобрал образ:

   <img width="975" height="334" alt="image" src="https://github.com/user-attachments/assets/43a60760-9927-4725-9941-26e67f4e6c1d" />

  
8. Запустил стек с помощью команды `docker compose up`.

   <img width="974" height="328" alt="image" src="https://github.com/user-attachments/assets/1554e79c-0e5b-4f2e-ad11-99b2169fca03" />
   <img width="980" height="306" alt="image" src="https://github.com/user-attachments/assets/39086fe4-fa70-4dc2-a3b3-b75cbc217ce4" />

9. Теперь, при переходе по ссылке `http://localhost:1234/` можно увидеть:

   <img width="593" height="218" alt="image" src="https://github.com/user-attachments/assets/51b9fda8-9a3d-48f3-8f56-080fae74ea10" />


---

# Заключение
#### В ходе лабораторной работы была изучена работа с программным обеспечением Docker для автоматизации развертывания и управления приложениями в средах с поддержкой контейнеризации.


