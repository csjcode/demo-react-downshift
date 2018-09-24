# demo-react-downshift
Demo of React Downshift - from Scotch



* npx create-react-app demo-react-downshift
* cd demo-react-downshift
* yarn add downshift axios react-popper
* Add css

```
	input {
      margin: 1rem;
      width: 20rem;
      padding: 1rem .5rem;
    }
    .downshift-dropdown {
      margin: 0 auto;
      width: 20rem;
      border: 1px solid whitesmoke;
      border-bottom: none;
    }
    .dropdown-item {
      padding: 0.5rem;
      cursor: pointer;
      border-bottom: 1px solid whitesmoke;
      font-size: 1rem;
      text-align: left;
    }
    .dropdown-button {
      padding: 0.6rem;
      border-radius: 3px;
      background: white;
      cursor: pointer;
    }
    .popper-div {
      flex: 1;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 5rem;
    }
    .popper-item {
      padding: .5rem;
      border-bottom: 1px solid whitesmoke;
    }
```

* When using Downshift, the only component we need is `<Downshift />` 





----------------------------------------------------------


