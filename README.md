### Simple react snippets

### rfc - React function component

```bash
import styles from './MyComponent.module.scss';
import { useState } from 'react';

export default function MyComponent() {
	const [data, setData] = useState();

	return (
		<div className={styles.container}>
			<div className={styles.content}>MyComponent</div>
		</div>
	);
};
```

### rcc - React Class Component

```bash
import styles from './MyComponent.module.scss';
import React from 'react';

export default class MyComponent extends React.Component {
	constructor(props) {
		super(props);
	};
	render() {
		return (
			<div className={styles.container}>
				<div className={styles.content}>MyComponent</div>
			</div>
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

### cl - class

```bash
class MyComponent {
	constructor(data) {
	Object.assign(this, data);
	}
};
```
