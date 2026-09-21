<h2>Nr. 2a)</h2>

```python
putPow()
while not rockFront():
	move()
turnRight()
turnRight()
while not onPow():
	move()
```

<h2>Nr.3</h2>

```python
while not onPow():
	while not rockFront():
		if not onPow():
			move()
	turnLeft()
	move()
	turnLeft()
	while not rockFront():
		if not onPow():
			move()
	turnLeft()
	turnLeft()
```