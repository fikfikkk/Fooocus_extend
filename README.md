# Fooocus_extend
Extender for Fooocus

(Any borrowing of code without attribution and permission of the author is considered plagiarism and disrespect for the author - if any are found, they will be indicated here)

(Любые заимствования кода без указания авторства и разрешения автора считается плагиатом и неуважением к автору - если такие найдутся, то будут здесь указаны)
<table>
  <tr>
    <td><a href="https://colab.research.google.com/github/shaitanzx/Fooocus_extend/blob/main/Fooocus_extend_wo_update.ipynb" rel="nofollow"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg"></a></td><td>Fooocus_extend without autoupdate. Base version 2.5.0</td>
  </tr>
  <tr>
    <td><a href="https://colab.research.google.com/github/shaitanzx/Fooocus_extend/blob/main/Fooocus_extend.ipynb" rel="nofollow"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg"></a></td><td>Fooocus_extend with autoupdate from original repository.</td>
  </tr>
  <tr>
    <td><a href="https://colab.research.google.com/github/lllyasviel/Fooocus/blob/main/fooocus_colab.ipynb" rel="nofollow"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg"></a></td><td>Original Fooocus Colab</td>
  </tr>
</table>

![image](https://github.com/user-attachments/assets/468487b8-8d4e-454c-ba92-1c9e5b60feb7)
![image](https://github.com/user-attachments/assets/d820cbbe-dd26-43fa-8ff7-79ece4733f69)
![image](https://github.com/user-attachments/assets/02cfefd2-7ab4-45ce-9a28-38cba008897c)
![image](https://github.com/user-attachments/assets/0dae1b83-d393-4601-ba7a-663a7e263c1c)
![image](https://github.com/user-attachments/assets/d8da2d79-73ea-476c-8c72-af4ec8351e08)
![image](https://github.com/user-attachments/assets/6b3cf591-b857-448c-bb8a-cf3f78429b11)



Сlick on the picture below to watch the video of previouse version


<a href="http://www.youtube.com/watch?feature=player_embedded&v=VuXzHu4PLsk
" target="_blank"><img src="http://img.youtube.com/vi/VuXzHu4PLsk/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Startup order
1. Select a profile
2. Select a theme (light, dark)
3. Memory_patch – reduces consumed video memory, which prevents errors when using various ImagePrompt modes
4. GoogleDrive_output – enable saving of all generation results to your Google Drive
5. Launch colab

Model Dowloader
1. CivitAI_API_KEY - required for downloading models from civitai.com It is best to use your personal key, not a third-party one, since if necessary, you can always view ONLY YOUR download history on the site. To do this, you need to register on the website civitai.com and then in the settings you can get the key.
2. Checkpoint Link – adding links to models from civitai.com. If you need to load several models, links to them can be specified separated by commas (,) without spaces
3. Lora Link - adding links to Lora from the site civitai.com. If you need to download several Loras, links to them can be specified separated by commas (,) without spaces.
4. Embedding Link - adding links to Embedding from the site civitai.com. If you need to download several Loras, links to them can be specified separated by commas (,) without spaces.
5. Start Download - start downloading all files via links
6. If CivitAI_API_KEY is absent, then the download not started
7. After downloading all the files, in the Model tab in Advanced mode, you need to update the list of models (click Refresh All Files)
8. To apply Embedding, in the prompt field use a record like (embedding:file_name:1.1)

Prompt Translate
1. Enable Translate - enable the extension
2. Translate - translation of the prompt into English without starting generation
3. Auto translate "Prompt and Negative prompt" before Generate - enable automatic translation of positive and negative prompts into English before generation
4. See translated prompts after click Generate - show translations of prompts after generation is completed

Photopea - online image editor

Remove Background - remove background from image

Порядок запуска
1.	Выбрать профиль
2.	Выбрать тему (светлая, темная)
3.	Memory_patch – уменьшает потребляемую видеопамять, что не позволяет вывалиться в ошибку при использовании различных режимов ImagePrompt
4.	GoogleDrive_output – включение сохранения всех результатов генераций на свой гуглдиск
5.	Запустить колаб

Model Dowloader
1.	CivitAI_API_KEY – необходим для загрузки моделей с civitai.com  Лучше всего использовать свой личный ключ, а не сторонний, так как в случае необходимости на сайте всегда можно посмотреть ТОЛЬКО СВОЮ историю загрузок. Для этого необходимо зарегистрироваться на сайте civitai.com и далее в настройках можно получить ключ.
2.	Checkpoint Link – добавление ссылок на модели с сайта civitai.com. При необходимости загрузки нескольких моделей, ссылки на них можно указывать через запятую (,) без пробелов
3.	Lora Link - добавление ссылок на Lora с сайта civitai.com. При необходимости загрузки нескольких Lora, ссылки на них можно указывать через запятую (,)  без пробелов.
4.	Embedding Link - добавление ссылок на Embedding с сайта civitai.com. При необходимости загрузки нескольких Lora, ссылки на них можно указывать через запятую (,)  без пробелов.
5.	Start Download - запуск скачивание всех файлов по ссылкам
6.	Если отстутсвует CivitAI_API_KEY, то загрузка производиться не будет
7.	После загрузки всех файлов, во вкладке Model в режиме Advanced, необходимо обновить список моделей (нажать Refresh All Files) 
8.	Для применения embedding, в поле промпта используйте запись типа (embedding:file_name:1.1)

Prompt Translate
1. Enable Translate - включение расширения
2. Translate - перевод промпта на англйский язык без запуска генерации
3. Auto translate "Prompt and Negative prompt" before Generate - включение автоматического перевода положительного и отрицательного промптов на английский язык перед генерацией
4. See translated prompts after click Generate - показывать переводы промптов после выполнения генерации

Photopea - онлайн редактор изображений

Remove Background - удаление фона с изображения


Change log

V3 (current version)
1. Add Photopea
2. Add Remove Background
3. Add Extention Panel
4. All extensions are available in Extention Panel

V2
1. Added a Model Downloader to Fooocus webui instead of colab

V1
1. added the ability to download models from the civitai.com
2. saving the generated image to Google Drive
3. added prompt translator
4. added a patch for the ability to work in free colab mode 
