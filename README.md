# Reading line-based JSON file
File should be like:
```
{ "a": 1, "b": 2 }
{ "a": 6, "b": 4 }
{ "a": 2, "b": 9 }
...
```
```python
records = [jsons.loads(line) for line in open(FILENAME)]
```

# Renaming a DataFrame column
```python
df.rename(columns={"old_name": "new_name"}, inplace=True)
```

# Setting a new DataFrame index
```python
df.set_index("INDEX", inplace=True)
```
