滚动条
```css
.x-scroller::-webkit-scrollbar
{
    height: 18px;
    width: 18px;
}

.x-scroller::-webkit-scrollbar:disabled
{
    display:none;
}

.x-scroller::-webkit-scrollbar-button
{
    background-color: #fff;
    background-repeat: no-repeat;
    cursor:pointer;
}

.x-scroller::-webkit-scrollbar-button:horizontal:increment,
.x-scroller::-webkit-scrollbar-button:horizontal:decrement,
.x-scroller::-webkit-scrollbar-button:horizontal:increment:hover,
.x-scroller::-webkit-scrollbar-button:horizontal:decrement:hover,
.x-scroller::-webkit-scrollbar-button:vertical:increment,
.x-scroller::-webkit-scrollbar-button:vertical:decrement,
.x-scroller::-webkit-scrollbar-button:vertical:increment:hover,
.x-scroller::-webkit-scrollbar-button:vertical:decrement:hover
{
    background-position:center;
    height: 18px;
    width: 18px;
}

.x-scrollerLight::-webkit-scrollbar-button
{
    display: none;
}

.x-scroller::-webkit-scrollbar-track
{
    background-color: #fff;
}

.x-scrollerLight::-webkit-scrollbar-track
{
    background-color: #0072C6;
}

.x-scroller::-webkit-scrollbar-thumb
{
    border-radius: 9px;
    border: solid 6px #fff;
    background-color: #c8c8c8;
}

.x-scrollerLight::-webkit-scrollbar-thumb
{
    border-color: #0072C6;
    background-color: #95B1C1;
}

.x-scroller::-webkit-scrollbar-thumb:vertical
{
    min-height:50px;
}

.x-scroller::-webkit-scrollbar-thumb:horizontal
{
    min-width:50px;
}

.x-scroller::-webkit-scrollbar-thumb:hover
{
    border-radius: 9px;
    border: solid 6px #fff;
    background-color: #98A3A6;
}

.x-scroller::-webkit-scrollbar-corner
{
    background-color: #fff;
}

```