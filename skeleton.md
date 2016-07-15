##What happens to the layout when you resize the screen to less than 550 px.How do you think that works? If you're stuck, discuss with your cohort in Slack.

####Larger than or equal with 550px:
```css
@media (min-width: 550px)
.one-half.column {
    width: 48%;
}
@media (min-width: 550px)
.column:first-child, .columns:first-child {
    margin-left: 0;
}
@media (min-width: 550px)
.column, .columns {
    margin-left: 4%;
}
@media (min-width: 550px)
.hero {
    padding-bottom: 12rem;
    text-align: left;
    height: 165px;
}
```
###Less than 550px:
```css
.column, .columns {
    width: 100%;
    float: left;
    box-sizing: border-box;
}
```
