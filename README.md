# Text-Translation-and-Summarization-App-from-Turkish-to-English
This project applies Gradio and HuggingFace Transformers to make a demo app applying translation and summarization tasks in series to a Turkish text for its English equivalent output. 

## Example:

## Full Turkish Text:
"Rusya'nın Ukrayna'ya yönelik işgal harekatı devam ederken, Ukrayna ordusunun son günlerde direnişini güçlendirdiği ve sahada bunun sonuçlarını almaya başladığı görülüyor. Nitekim Ukrayna’nın, önceki gece ilk kez Rusya topraklarında bir saldırıya giriştiği ve helikopterlerle Belgorod'daki yakıt deposunu vurduğu ifade ediliyor. Medya ve sosyal medyada yer alan görüntülerde, helikopterlerin depoyu vurdukları ve daha sonra bölgeden uzaklaştıkları görülüyor."

## English Summarized output:
"Russia's new igal operation to Ukraine continues. Ukraine's army has raised its resistance in the last moments, and is taking the end of it in the field. Ukraine, for the first time in the night, it is said to have hit the fuel warehouse in Belgorod with helicopters."

## Notes: 
Since the linking of two models in series is relatively a new approach, result is not perfect since there are some mistakes in translation of some words (e.g, "işgal >> igal), and in grammar related to syntax (e.g, using "it" in the last sentence to refer to Ukraine, while there is actually no need). However, as can be seen from the example above, the result is impressive nevertheless meaning that if further advancements are made in this approach, much more satisfying results could be attained.

* The link to the site where I got the sample paragraph: https://www.milliyet.com.tr/gundem/ukraynadan-karsi-saldiri-6729915#:~:text=Rusya%27n%C4%B1n%20Ukrayna%27ya%20y%C3%B6nelik,b%C3%B6lgeden%20uzakla%C5%9Ft%C4%B1klar%C4%B1%20g%C3%B6r%C3%BCl%C3%BCyor.
