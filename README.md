# mock-phone
Simple css solution to mock phone

## How to use
Add below css and apply class 'mock-phone' an element and a phone will appear ;-)
See index file for example.

```css
.phone-mock::before {
    content: "";
    display: block;
    position: absolute;
    height: 120%;
    width: 110%;
    top: -10%;
    left: -5%;
    border-radius: 30px;
    background-color: grey;
    z-index: -1;
}
.phone-mock::after {
    content: "";
    display: block;
    position: absolute;
    width: 10%;
    padding-bottom: 10%;
    background: #aaa;
    top: 102%;
    left: 45%;
    box-sizing: content-box;
    border-radius: 100%;
}
```