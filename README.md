# DAY 2: REM AND EM 

Both rem and em are relative units that can be used to make your site responsive. 

- `rem` means root em, which means it always derives its value from the root element, which is `html`. 
- `em` value depends on the parent. 

## SETTING FONT-SIZE WITH EM AND REM

Setting font-size with `em` can result in unexpected results most times. This is because `em` compounds its value from all of its parent elements, and things can quickly grow really big in a nested relationship. 

`rem`, on the other hand, is fixed and will always get its value from the root `html`.

## SETTING MARGIN AND PADDING WITH EM AND REM

When setting padding and margin, `em` derives its value from the font-size of its parent element. For example, if the parent element font-size is `12px`, then `2em` will be `2 x 12 = 24px`. 

With this, you can make your website's padding and margin responsive, adjusting according to the font-size. 

