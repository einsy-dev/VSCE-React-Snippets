### Simple react snippets

### rfc - React function component

```bash
import styles from './MyComponent.module.scss';
import { useState } from 'react';

export default function MyComponent() {
	const [data, setData] = useState();

	return (
		<div className={styles.container}>
			<div className={styles.content}>MyComponent$1</div>
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
				<div className={styles.content}>MyComponent$1</div>
			</div>
		);
	};
};

```

### ue - useEffect

```bash
useEffect(() => {
	$1
}, []);

```

### rs - redux useSelector

```bash
const $1 = useSelector($2);

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
console.log($1)
```

### ef - export from

```bash
export { $1 } from '.$2';

```

### exp - export

```bash
export { $1 };

```

### ed - export default

```bash
export default $1;

```

### fd - function declaration

```bash
function MyComponent() {
	$1
};

```

### fe - function expression

```bash
const MyComponent = function() {
	$1
};

```

### af - arrow function

```bash
($1) => { $2 }
```

### cla - class

```bash
class MyComponent {
	constructor(data) {
	Object.assign(this, data);
	}
	$1
};

```
