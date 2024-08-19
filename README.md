# Photo Organizer
Photo Organizer е приложение, създадено за сортиране и организиране на вашата фото колекция въз основа на датата, на която са заснети снимките. Този инструмент поддържа различни формати на изображения, включително RAW формати от популярни производители на фотоапарати.
Функции:
Извличане на EXIF данни: Автоматично чете EXIF данни от JPEG изображения, за да определи датата на заснемане на снимката.
Поддръжка на RAW формати: Работи с различни RAW формати на изображения (например .CR2, .NEF, .ARW), използвайки rawpy за извличане на информация за датата.
Организация по дата: Сортира снимките в папки, именувани по година, месец и ден въз основа на извлечената дата.
Алтернативно сортиране: Ако EXIF данни не са налични, програмата използва последната дата на модификация на файла като резервен вариант.
Интуитивен интерфейс: Предлага лесен графичен потребителски интерфейс (GUI) за избор на папката, съдържаща вашите снимки, и за стартиране на процеса на сортиране.

Photo Organizer is application designed to sort and organize your photo collection based on the date the photos were taken. This tool supports various image formats, including RAW formats from popular camera manufacturers.
Features:
EXIF Data Extraction: Automatically reads EXIF data from JPEG images to determine the date the photo was taken.
RAW Format Support: Handles multiple RAW image formats (e.g., .CR2, .NEF, .ARW) using rawpy to extract date information.
Date-based Organization: Sorts photos into folders named by year, month, and day based on the extracted date.
Fallback Sorting: If EXIF data is not available, the program uses the file’s last modification date as a fallback.
User-Friendly Interface: Provides a simple graphical user interface (GUI) to select the folder containing your photos and initiate the sorting process.
