# FP_Lab_0
В ходе лабораторной работы я изучил различные варианты функциональных языков программирования. Прежде всего надо было понять, для чего именно мне нужен этот самый язык. Потому первым шагом стала разработка идеи для написания 4 лабораторной работы. Объединившись с моим одногруппником, мы решили, что будем писать многопользовательскую 2D игру "Танки в лабиринте". 

Для этого нам нужен будет фронт- и бекенд. В нашей команде роль бекенд-разработчика досталась мне, поэтому нужен был язык, подходящий именно для него. Область применения известна, теперь можно было пройтись уже более предметно по языкам и решить, какой больше мне подходит. Понимая задачу и здраво оценив свой математический потенциал, я понял, что лезть в ЯП теоретической направленности(Coq и ему подобные проходят мимо) и Agda не стоит. 

Для решения моей задачи подойдут такие языки как Common Lisp, Clojure, OCaml, Haskell и F#.  Из данного перечня выбор пал на F#, так как он обладает строгой статической типизацией, что помогает раньше выявлять ошибки, компилятор точно знает, где какой тип. Также важным фактором являет глубокая интеграция в систему .NET, что позволит разрабатывать кроссплатформенные решения, пользоваться возможностями .NET SDK, а также безболезненно прейти в будущем на C#, многие принципы в них похожи. Приятным бонусом является полная поддержка F# в VS и JetBrains Rider.


Компилятор - fsc  
Система сборки - SDK  
Система автоматического форматирования - Fantomas  
Lint tool - F# Lint  
Тестирование - MSTest, xUnit  

Кника для изучения: Программирование на F# - Крис Смит  

Список литературы:
1. https://habr.com/ru/articles/105215/ - веб Common Lisp
2. https://qna.habr.com/q/698051 - Common Lisp vs F#
3. https://learn.microsoft.com/ru-ru/visualstudio/msbuild/customize-your-build?view=vs-2022 - MSBuild
4. https://learn.microsoft.com/ru-ru/dotnet/fsharp/what-is-fsharp - F#
5. https://learn.microsoft.com/ru-ru/dotnet/core/introduction - .NET
6. https://learn.microsoft.com/ru-ru/shows/build-2018/thr2025-1 - Почему вам стоит использовать F#
7. https://metanit.com/f/tutorial/1.1.php - F#
8. https://learn.microsoft.com/en-us/dotnet/fsharp/style-guide/ - F# style guide
9. https://habr.com/ru/articles/280410/ - тестирование в F#
10. https://ru.wikipedia.org/wiki/OCaml - OCaml
11. https://eax.me/haskell-vs-ocaml/ - Haskell vs OCaml
12. [8 months of OCaml after 8 years of Haskell in production - DEV Community](https://dev.to/chshersh/8-months-of-ocaml-after-8-years-of-haskell-in-production-h96) - Haskell vs Ocaml
13. https://clojure.org/ - Clojure
14. [Clojure, или «Вы все еще используете Java? Тогда мы идем к вам!» (fprog.ru)](https://fprog.ru/2010/issue4/alex-ott-clojure/) - Clojure
