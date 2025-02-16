# Основы Java

<p>
<control>В этом разделе мы будем рассматривать основы Java 
такие, как объявления переменных, классов, методов и прочее</control> 
</p>
<p>
    Как 
</p>
## Объявление переменных
<p>
Давайте рассмотрим несколько различных типов переменных которыми мы обладаем
</p>
    <tabs group="os">
    <tab id="Int" title="Целое число" group-key="int">
        <code-block lang="java">
            int i = 0;
            long l = 0;
        </code-block>
    </tab>
    <tab id="Double" title="Вещественное число" group-key="double">
        <format style="subscript">Вещественные числа - числа с дробной частью</format>
        <code-block lang="java">
            double d = 0;
            float f = 0f;
        </code-block>
    </tab>
    <tab id="String" title="Строка" group-key="string">
        <code-block lang="java">
            String str = 0;
        </code-block>
    </tab>
    <tab id="Object" title="Объект" group-key="obj">
        <code-block lang="java">
            Object obj = new Object();
        </code-block>
    </tab>
</tabs>

<p>
Как можно заметить все они называются либо 1 маленькой буквой, либо словом начинающегося с 
маленькой буквы. Это принято всеми программистами на Java, все переменные пишутся в стандарте <code>camelCase</code>.
</p>
<p>
Также на фоне других переменных выделяется Object, это как не сложно перевести объект, тоесть
на его месте может быть любой класс. Например:
</p>
<code-block lang="java">
            Mechanism mechanism = new Mechanism();
</code-block>
<p>
Также на общем фоне выделяется тип float требующий f в конце числа для его определения
</p>
<p>
Единственная разница между int/long и double/float это объем хранимых в них данных.
Однако я обычно использую исключительно int и double
</p>

## Объявление классов
<p>
Но где же мы будем хранить наши переменные. А хранить мы их будем внутри классов.

</p>



