# Stereogene-Testing
Test stereogene in order to account chromatin presence




# Данные
~  =  /home/ilya  
Есть куча ридов из баз  ->  Они сведены в GTRD  ->  Проводится коллинг пиков 4мя способами. Получаем ChIP-seq пики * 4  

**Отсюда:**
1. Модели hocomoco  
~/mouse_enhancers_specificity/sites/..    
-> Получаем разметку мотвами  
2. Цистром. Это агрегация пиков и сортировка по качеству(highest, high, medium)  
~/cistrome_markup/source_data/gtrd  

**В итоге:**
Получаем разметку цистрома вхождениями мотива. То есть мы подтвердили вхождения мотивов на чипсеках  
~/cistrome_markup/results/..  
	
	
	
	
# Вопросы
Мой главный вопрос это какие данные мне скармливать стереогену.  




# ToDo
## Global 
**Test task**
- насколько хорошо коррелирует пик чипсека с вхождением мотива. Все знают, что коррелируют 

**Actual goal**
 - это многострадальное сравнение чипсека фактора с чипсеком нуклеосомы, чтобы понять, коррелируюет ли  расположение фактора с нуклеосомой или нет. 
 
## Current stage
**todo**
Запустить стереоген на тестовых данных, разобраться в его работе.




# Статьи и ссылки
## Описания форматов файлов
source: https://genome.ucsc.edu/FAQ/FAQformat.html

## StereoGene, 2017
github: https://github.com/favorov/stereogene  
publication: https://www.biorxiv.org/content/early/2017/05/25/059584  
docs: http://stereogene.bioinf.fbb.msu.ru/  

Highlights
 - Stats: Kernel correlation (KC)
 - Stat-Test: Permutation test
 - Data-input: BED, WIG, BedGraph, BroadPeak

## DNA Sequence Preferences of Transcriptional Activators Correlate More Strongly than Repressors with Nucleosomes 27.07.2012
name: The interaction landscape between transcription factors and the nucleosome
publication: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3566590/

Highlights
 - Различия в регуляции транскрипции у прокариот(сила связывания между [RNApoly + TF] & [DNA]) и эукариот(доступность DNA на фоне хроматина)
 - Досупность TFBS ~ расположение нуклеосом
 - seq-specific TF & chromatin remodeling factors can increase TF accesibility
 - prediction of nucleosome dynamics can be enhanced by itegrating TF binding information
 - there is no good model for nucleosome-TF interactions

##The interaction landscape between transcription factors and the nucleosome 29.12.2017
name: The interaction landscape between transcription factors and the nucleosome
publication: https://www.biorxiv.org/content/early/2017/12/29/240598

Highlights

