# Bag-of-Words
Дан набор предложений [sentenses.txt], скопированных с Википедии. Каждое из них имеет "кошачью тему" в одном из трех смыслов:
 + кошки (животные)
 + UNIX-утилита cat для вывода содержимого файлов
 + версии операционной системы OS X, названные в честь семейства кошачьих

Задача — найти два предложения, которые ближе всего по смыслу к расположенному в самой первой строке. В качестве меры близости по смыслу использовать косинусное расстояние.
