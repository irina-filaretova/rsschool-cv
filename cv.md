# Filaretova Irina

## Contacts for communication
* email: filaretova.irina@mail.ru
* telegram: [@filaretovairina](https://t.me/filaretovairina)

## Brief information about yourself
### Purpose
Become a skilled frontend developer capable of creating interactive and user-friendly web interfaces using modern technologies and frameworks. 
### Strengths
* Fast learner: Motivated and eager to continuously develop in the field of web development.
* Communication skills: Willingness to work in a team and communicate with colleagues to share experiences and solve problems.
* Creativity: Openness to new ideas and desire to create beautiful and functional interfaces.

## Skills
* HTML and CSS basics
* Working in the VSCode editor

## Code example
```
function Card() {
    useCheckAuth();
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
## Work experience
* [Training project website business card](https://gitlab.com/IrinaFilaretova/business_card)
* [Online store training project](https://gitlab.com/IrinaFilaretova/module-react)

## Education
Underwent professional retraining in ANOE VO "Innopolis University" on an additional professional program "Frontend development basics"

## English
The level of English is basic.