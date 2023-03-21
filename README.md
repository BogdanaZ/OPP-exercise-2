# OPP-exercise-2

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/opp-team-dom-iagcaq)

## 1. Dom

a) in home component add a svg/image that is animated with pure css (use keyframes) also below explaind how you created that animation
b) Create a component with route where you use ng-content, ng-container, ng-template and \*ngTemplateOutlet. Add a link in the navigation for that component
(be prepare to explained why did you use, what you used)

## 2. Forms

Create a new component and added in the navigation
The component will contain a form with:

- 2 inputs with label for name and surname
- 1 dropdown with a label to pick up a county (judete) -> https://roloca.coldfuse.io/judete
- Button to submit the form (show in a console log)
- Button disabled until all the fields are validated(no empty)
- The data must be taken automatically from the endpoint (use http, not copy/paste)

## 3. Forms add on

On the same component from the previous point:

- add another 1 dropdown with a label to pick up a village/city -> https://roloca.coldfuse.io/orase/[CountyCode]
  ex: https://roloca.coldfuse.io/orase/BN .
  The values for this filed depend on the other dropdown
- modify the button to contained also the new filed validation

### 4. Custom Validation

On the same component from the previous points:

- Create a input field with a label for a phone number.
- Add a custom validation to this input by matching this formula :

```bash
  Accepts 12 or 13 characters
  Should start with either + or 00
  Then accepts another 11 numeric characters
```

- If the condition is not met an errors appears underneath the input with a text massage
- The check is done on keyup, not when clicking the button
- modify the button to contained also the new filed validation
