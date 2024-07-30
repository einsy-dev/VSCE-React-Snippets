### Simple react snippets

### rfc - React function component

```bash
import { useState } from 'react'

export default function Index() {
	const [data, setData] = useState()

	return (
		<div className={styles.container}>
			Index
		</div>
	);
};
```

### rcc - React Class Component

```bash
import React from 'react';

export default class MyComponent extends React.Component {
	constructor(props) {
		super(props);
	};
	render() {
		return (
			<div>MyComponent</div>
		);
	};
};
```

### ue - useEffect

```bash
useEffect(() => {

}, []);
```

### rs - redux useSelector

```bash
const $1 = useSelector((state) => state.$2);
```

### rd - redux useDispatch

```bash
const dispatch = useDispatch();
```

### rrn - react router dom useNavigate

```bash
const navigate = useNavigate();
```

### clg - console log

```bash
console.log($1);
```

### ef - export from

```bash
export { $1 } from './$1'
```

### e - export

```bash
export { $1 }
```

### ed - export default

```bash
export default
```

### fd - function declaration

```bash
function MyComponent() {
};
```

### fe - function expression

```bash
const $1 = function() {

};
```

### af - arrow function

```bash
() => {
};
```

### class - class

```bash
class MyComponent {
	constructor(data) {
	Object.assign(this, data);
	}
};
```
