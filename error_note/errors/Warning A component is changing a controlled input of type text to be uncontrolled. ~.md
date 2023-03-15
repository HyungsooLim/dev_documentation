___
## Error Name
- Warning: A component is changing a controlled input of type text to be uncontrolled. Input elements should not switch from controlled to uncontrolled (or vice versa). Decide between using a controlled or uncontrolled input element for the lifetime of the component.
## Reason
- input의 value에 `undefined`가 할당되어 나는 원인.
## Solution
1. value에 `undefined`가 할당되지 않게 수정.