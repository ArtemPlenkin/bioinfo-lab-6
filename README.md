# Задание 6. Предсказание и парное выравнивание структур белков

Последовательность: `MSTLTSVSGFPRIGQNRELKKIIEGYWKGANDLAAVKATAAELRAKHWRLQQAAGIDLIASNDFSYYDQMLDTAILLNVIPQRYQRLAFDDQEDTLFAMA`

Программы-предсказатели: **AlphaFold2, OmegaFold**

Инструмент парного выравнивания: **ProFit**

Полученные notebooks: [AlphaFold2.ipynb](/AlphaFold2.ipynb) и [omegafold.ipynb](/omegafold.ipynb)

Результаты предсказаний находятся в папках [AlphaFold2_results](/AlphaFold2_results) и [omegafold_results](/omegafold_results)

Предсказания, которые использовались для выравнивания: `AlphaFold2_results/test_3b0d9_unrelaxed_rank_3_model_1.pdb` и `omegafold_results/test_3b0d9.pdb`

В качестве результата прогонки файлов через ProFit (веб-версия) были две ссылки на веб-страницы с последовательностями атомов и их координат. Скопировав полученные последовательности и сохранив их в формате .pdb, я и получил результат парного выравнивания: [Profit_results](/ProFit_results)

![profit_res](/ProFit_results/profit_result.png)

Загрузил полученные последовательности в ChimeraX для визуализации и раскрасил две структуры в разные цвета:

![chimerax](/chimera.png)


## Выводы
*С помощью полученного выравнивания мы можем видеть, что предсказания близки, но всё таки имеются некоторые отличия*
