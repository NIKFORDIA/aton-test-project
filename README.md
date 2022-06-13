Проект для отклика на позицию стажёра-верстальщика по программе ITTP-2022 (Information Technology Talent Program)
Красильников Е.А. zhenyakrasil@mail.ru

Ссылка на макет Figma: https://www.figma.com/file/CUTc8mySy8mbjZRk8RQorE/%D0%A2%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D0%BE%D0%B5-%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5

Макет, представленный в Figma, реализован для разрешения экрана 1440px (max-width: 1440px), для бо́льших значений добавлены белые поля с боковых сторон, для меньших значений реализована адаптивная и кроссбраузерная вёрстка, включающая в себя изменения, касающиеся всех основных блоков страницы: подобраны размеры шрифтов, порядок распределения элементов, различные отступы и прочие детали, позволяющие пользователю корректно использовать сайт с любых устройств, даже с разрешением экрана меньшим, чем 320px (вплоть до 240px).

Чтобы реализовать адаптивную вёрстку, пришлось в одном месте отступить от заложенного в Figme дизайна: тень от шапки сайта (footer) падает только на размытые фото. Чтобы реализовать задумку макета, пришлось бы основную фотографию задавать абсолютно, что позволило бы добиться полного совпадения с макетом, но не дало бы реализовать адаптивную вёрстку. Прописывать значение absolute для одного-единственного значения ширины экрана (1440px), а для <1439px и >1441px обратно возвращаться к относительному посчитал нецелесообразным. Если требуется реализовать - без проблем могу доработать.

Ссылка на GitHub Pages: https://nikfordia.github.io/aton-test-project/
