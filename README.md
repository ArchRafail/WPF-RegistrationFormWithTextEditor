# WPF-RegistrationFormWithTextEditor</br>
</br>
Панели инструментов. Текст и документы</br>
</br>
Необходимо разработать приложения, которое позволяло бы устанавливать разнообразные настройки</br>
форматирования заданным участкам текста.</br>
</br>
В верхней части окна должна располагаться панель инструментов, содержащая элементы управления</br>
форматирования текста.</br>
Для указания диапазона (фрагмента) текста необходимо использовать два поля для ввода текста,</br>
в которых будут задаваться индексы первого и последнего символа входящих в диапазон. Данные</br>
поля для ввода текста должны позволять вводить только положительные числа и ноль.</br>
В случае указания некорректного диапазона (например, начальный индекс больше конечного или</br>
индекс за пределами текста), все остальные элементы управления на панели задач должны стать</br>
неактивными.</br>
</br>
■ Кнопка «Bold» должна делать текст в выбранном диапазоне жирным.</br>
■ Кнопка «Italic» должна делать текст в выбранном диапазоне курсивным.</br>
■ Кнопка «Underline» должна делать текст в выбранномдиапазоне подчеркнутым.</br>
■ Кнопка «Clear» должна снимать все установленные настройки форматирования для текста в выбранном</br>
диапазоне (стиль текст, цвет и размер шрифта).</br>
</br>
При выборе элемента из выпадающих списков, отвечающих за размер шрифта и его цвет, необходимо</br>
устанавливать соответствующее форматирование тексту в выбранном диапазоне.</br>
Настройки форматирования могут накладываться друг на друга. Например, если в выбранном диапазоне</br>
содержится подчеркнутый текст и пользователь нажимает кнопку «Italic», то текст останется подчеркнутым,</br>
но при этом станет еще и курсивным.</br>
</br>
The program unites 2 programs that realised in 2 different tabs.</br>
There are registration form if the first tab and text editor in the second.</br>
Registration form described at program WPF-RegistrationForm on the other branch (https://github.com/ArchRafail/WPF-RegistrationForm.git)</br>
Text editor will allow you change the format of the text (TextStyle, TextDecoration, FontSize, FontColor).</br>
Text is picked from the indexes of the start position in whole text and the end position.</br>
You can any time pick new text and it will be highlited in the text block.</br>
After that you can change format of the text and clear all formats.</br>
Have fun!</br>
