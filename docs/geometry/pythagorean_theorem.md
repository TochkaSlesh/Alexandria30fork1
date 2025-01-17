# Теорема Пифагора

!!! note "Заметка"
    Данная теорема была помечена как *судьбоносная* несколькими учителями тридцатки

!!! note "Заметка"
    В этой статье представлены самые простые способы доказательства

## Формулировка {#формулировка}

В прямоугольном, и только в прямоугольном треугольнике квадрат длины гипотенузы равен сумме квадратов длин катетов

## Доказательство {#доказательство}

<figure markdown="span">
    ![Данный треугольник](../assets/geometry/pythagorean-theorem/given_triangle.svg "Данный треугольник")
    <figcaption>Дан прямоугольный треугольник с гипотенуузой *c*, катетами *a* и *b*</figcaption>
</figure>

## Прямое утверждение {#прямое-утверждение}

В прямоугольном треугольнике квадрат длины гипотенузы равен сумме квадратов длин катетов

### 1 способ {#способ1}

Сделаем дополнительное построение

<figure markdown="span">
    ![Дополнительное построение](../assets/geometry/pythagorean-theorem/way1.svg "Дополнительное построение")
    <figcaption>Квадрат со стороной *a* + *b*</figcaption>
</figure>

Треугольники *△AKL*, *△BMK*, *△CNM* и *△DLN* равны по 2м катетам

*KMNL* тоже квадрат, поскольку острые углы в прямоугольном треугольнике в сумме дают 90° и все стороны равны *c*

С одной стороны площадь *ABCD* равна произведению его сторон

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

$\begin{array}{ll}
    (a + b)^2 = a(a + b) + b(a + b) = a^2 + 2ab + b^2
\end{array}$

</div>

<figure markdown="span">
    ![ФСУ](../assets/geometry/pythagorean-theorem/faster_multiplication_formulas.svg "ФСУ")
    <figcaption>$(a + b)^2 = a^2 + 2ab + b^2$</figcaption>
</figure>

С другой стороны равна сумме площадей фигур, из которых он состоит

$4 \cdot \frac{1}{2} \cdot ab + c^2$

Подставим

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

$\begin{array}{ll}
    a^2 + 2ab + b^2 = 4 \cdot \frac{1}{2} \cdot ab + c^2 \iff \\
    a^2 + 2ab + b^2 = 2ab + c^2 \iff \\
    c^2 = a^2 + b^2
\end{array}$

</div>

### 2 способ (доказательство Гарфилда) {#способ2-гарфилд}

Сделаем дополнительное построение

<figure markdown="span">
    ![Дополнительное построение](../assets/geometry/pythagorean-theorem/way2.svg "Дополнительное построение")
    <figcaption>Прямоугольная трапеция с основаниями *a* и *b*, высотой *a* + *b*</figcaption>
</figure>

Треугольники *△ABK*, *△DKC* равны по 2м катетам

$\angle$*BKC* = 90° т. к. острые углы треугольника в сумме равны 90°

С одной стороны площадь *ABCD* равна произведению полусуммы оснований на высоту

$(a + b) \cdot \frac{a + b}{2} = \frac{(a + b)^2}{2}$

С другой стороны равна сумме площадей фигур, из которых она состоит

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

$2 \cdot \frac{1}{2} \cdot ab + \frac{1}{2} \cdot c \cdot c = \frac{c^2 + 2ab}{2}$

</div>

Подставим

$\begin{array}{ll}
    \frac{(a + b)^2}{2} = \frac{c^2 + 2ab}{2} \iff \\
    a^2 + 2ab + b^2 = 2ab + c^2 \iff \\
    c^2 = a^2 + b^2
\end{array}$

### 3 способ {#способ3}

Сделаем дополительное построение

<figure markdown="span">
    ![Дополнительное построение](../assets/geometry/pythagorean-theorem/way3.svg "Дополнительное построение")
    <figcaption>Квадрат со стороной *с*. Внутри 4 исходных треугольника, построенных на стороне квадрата, как на гипотенузе</figcaption>
</figure>

*KIJL* тоже квадрат, поскольку все его углы смежные с углами 90° и все стороны равны *a* - *b*

С одной стороны площадь *ABCD* равна произведению его сторон $c^2$

С другой стороны равна сумме площадей фигур, из которых она состоит

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

$4 \cdot \frac{1}{2} \cdot ab + (a - b)^2 = a^2 + b^2 + 2ab - 2ab = a^2 + b^2$

</div>

Получается

$c^2 = a^2 + b^2$

## Теорема, обратная теореме Пифагора {#обратная-теорема}

Если в треугольнике со сторонами *a*, *b* и *c* выполняется $c^2 = a^2 + b^2$, то угол напротив *c* - прямой

![Обратная теорема](../assets/geometry/pythagorean-theorem/converse.svg "Обратная теорема")

Предположим что это не так: $\angle C \neq 90^\circ$

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

Тогда построим треугольник △$A_1 B_1 C_1$ так, чтобы $\angle C_1 = 90^\circ; |B_1 C_1| = a; |A_1 C_1| = b$.
Тогда $|A_1 C_1| = \sqrt{a^2 + b^2} = |AC|$

</div>

*△ABC* = △$A_1 B_1 C_1$ по трем сторонам, но тогда $\angle C = 90^\circ$ - противоречие

---

Над статьей работали:

- Чухалёнок Алексей ([Тг](https://t.me/AlexeyRoot)): редактор
- Валентин Андреевич ([Страничка в тридцатке](https://school30.spb.ru/staff/~evstafyevva.shtml)): магистр-джедай

Выражаем благодарность:

- Пифагору ([Wiki](https://en.wikipedia.org/wiki/Pythagoras)), за эту шедевро-теоремку
- Джеймсу Гарфилду ([Wiki](https://en.wikipedia.org/wiki/James_A._Garfield)), за одно из доказательств этой теоремы
