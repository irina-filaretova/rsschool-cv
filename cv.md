# Филаретова Ирина

## Контакты для связи
* email: filaretova.irina@mail.ru
* telegram: [@filaretovairina](https://t.me/filaretovairina)

## Краткая информация о себе
### Цель
Стать квалифицированным frontend разработчиком, способным создавать интерактивные и удобные веб-интерфейсы, применяя современные технологии и фреймворки. 
### Сильные стороны
* Быстрое обучение: Мотивация и стремление к постоянному развитию в области веб-разработки.
* Коммуникабельность: Желание работать в команде и общаться с коллегами для обмена опытом и решения задач.
* Креативность: Открытость к новым идеям и желание создавать красивые и функциональные интерфейсы.

## Навыки
* Основы HTML и CSS
* Работала в редакторе VSCode

## Пример кода
```
function Card() {
    useCheckAuth(); // проверка авторизован ли пользователь
    const { id } = useParams();
    const { onAddToBasket, quantity, sum, currentItem } = useLoadBasket(id);

    return (
        <div className={styles.products}>
            <div className={styles.products__wrapper}>
                <Header 
                    showBasket
                    hasPrev
                    title=""
                    quantity={quantity}
                    sum={sum}
                />
                <div className={styles.products__list}>
                        <CardPreview
                            key={currentItem.id}
                            id={currentItem.id}
                            url={currentItem.url}
                            title={currentItem.title}
                            desc={currentItem.desc}
                            price={currentItem.price}
                            quantity={currentItem.quantity}
                            onAddToBasket={onAddToBasket}
                        />
                </div>
            </div>
        </div>
    )
}

```
## Опыт работы
* [Учебный проект сайт визитка](https://gitlab.com/IrinaFilaretova/business_card)
* [Учебный проект интернет магазина](https://gitlab.com/IrinaFilaretova/module-react)

## Образование
Прошла профессиональную переподготовку в АНО ВО "Университет Иннополис" по дополнительной профессиональной программе "Основы Frontend-разработки"

## Английский язык
Уровень английского языка - базовый.