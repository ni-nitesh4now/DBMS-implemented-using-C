# Key-Value Database Management System

A basic key-value database management system implemented in C. This program allows users to perform operations like putting a key-value pair, getting the value for a key, deleting a key, clearing the entire database, and viewing all key-value pairs.

## How to Execute

1. **Compile the Code:**
```gcc -o keyval_db keyval_db.c```

2. **Run the Program:**
``` ./keyval_db [command1] [command2] ...```

   Replace `[command1]`, `[command2]`, etc., with the desired commands. See the next section for available commands.

## Commands

- **Put a Key-Value Pair:**
  ```./keyval_db p [key] [value]```

- **Get the Value for a Key:**
  ```./keyval_db g [key]```

- **Delete a Key:**
  ```./keyval_db d [key]```

- **Clear the Entire Database:**
  ```./keyval_db c```

- **View All Key-Value Pairs:**
  ```./keyval_db a```

## Input Formats

- **Put Command:**
  ```./keyval_db p [key] [value]```

- **Get Command:**
  ```./keyval_db g [key]```

- **Delete Command:**
  ```./keyval_db d [key]```

- **Clear Command:**
  ```./keyval_db c```

- **All Command:**
  ```./keyval_db a```

## Example Usage

```
./keyval_db p 1 value1
./keyval_db p 2 value2
./keyval_db g 1
./keyval_db d 2
./keyval_db a
./keyval_db c
```



All the data is stored in db.txt file. You can view it by typing ```cat db.txt```#   D B M S - i m p l e m e n t e d - u s i n g - C  
 