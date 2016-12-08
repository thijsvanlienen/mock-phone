# mock-phone
Simple css solution to mock phone

## How to use
Apply these styles to any a element and a phone will appear.

```css
section.preview-container::before {
    content: "";
    display: block;
    position: absolute;
    height: 100%;
    width: 100%;
    top: -50px;
    left: -15px;
    border: 50px solid grey;
    border-left: 15px solid grey;
    border-right: 15px solid grey;
    box-sizing: content-box;
    border-radius: 40px;
    border-bottom: 100px solid grey;
}
section.preview-container::after {
    content: "";
    display: block;
    position: absolute;
    height: 50px;
    width: 50px;
    background: #aaa;
    top: 103%;
    left: 44%;
    box-sizing: content-box;
    border-radius: 100%;
}
```