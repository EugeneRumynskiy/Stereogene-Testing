# Stereogene-Testing
Test stereogene in order to account chromatin presence

# Данные

В общем, мой главный вопрос это какие данные мне скармливать стереогену.

Есть куча данных из баз -> Они сведены в GTRD -> Далее, коллинг пиков 4мя способами и мы получили ChIP-seq

Отсюда:
A - мы получаем модели hocomoco
B - Агрегация пиков по качеству и сортировка по качеству  - цистром.

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

