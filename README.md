# Stereogene-Testing
Test stereogene in order to account chromatin presence

# Данные
~  =  /home/ilya  

Мой главный вопрос это какие данные мне скармливать стереогену.  

Есть куча ридов из баз  ->  Они сведены в GTRD  ->  Проводится коллинг пиков 4мя способами. Получаем ChIP-seq пики * 4  


Отсюда:
1. Модели hocomoco  
~/mouse_enhancers_specificity/sites/..    
-> Получаем разметку мотвами  
2. Цистром. Это агрегация пиков и сортировка по качеству(highest, high, medium)  
~/cistrome_markup/source_data/gtrd  


В итоге:  
Получаем разметку цистрома вхождениями мотива. То есть мы подтвердили вхождения мотивов на чипсеках  
~/cistrome_markup/results/..  
	

# ToDo

Запустить стереоген на тестовых данных, разобраться в его работе.

# Статьи

## StereoGene, 2017
github: https://github.com/favorov/stereogene  
publication: https://www.biorxiv.org/content/early/2017/05/25/059584  
docs: http://stereogene.bioinf.fbb.msu.ru/  

Highlights
 - Stats: Kernel correlation (KC)
 - Stat-Test: Permutation test
 - Data-input: BED, WIG, BedGraph, BroadPeak

## Статья про нуклеосомы, 2012
publication: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3566590/

Highlights
 - Различия в регуляции транскрипции у прокариот(сила связывания между [RNApoly + TF] & [DNA]) и эукариот(доступность DNA на фоне хроматина)
 - Досупность TFBS ~ расположение нуклеосом
 - seq-specific TF & chromatin remodeling factors can increase TF accesibility
 - prediction of nucleosome dynamics can be enhanced by itegrating TF binding information
 - there is no good model for nucleosome-TF interactions

