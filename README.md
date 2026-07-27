# 📞 Phonebook App

A simple **Phonebook Management System** developed in **C** using a **Singly Linked List**. This application allows users to store, search, delete, and display contact information efficiently through a menu-driven interface.

## 📌 Features

- ➕ Add new contacts
- 🔍 Search contacts by name
- 📋 Display all saved contacts
- ❌ Delete contacts
- 📱 Phone number validation
- 💾 Dynamic memory allocation using linked lists

## 🛠️ Technologies Used

- C Programming
- Singly Linked List
- Dynamic Memory Allocation
- GCC Compiler

## 📂 Project Structure

```
Phonebook-App/
│── phonebook.c        # Source code
│── README.md          # Project documentation
```

## 🚀 How to Run

### Compile

```bash
gcc phonebook.c -o phonebook
```

### Execute

```bash
./phonebook
```

**Windows**

```bash
gcc phonebook.c -o phonebook.exe
phonebook.exe
```

## 📋 Menu Options

```
1. Save a Contact
2. Delete a Contact
3. Display All Contacts
4. Search Contact
0. Exit
```

## 📖 Data Structure Used

The application uses a **Singly Linked List**, where each node stores:

- Contact Name
- Phone Number
- Pointer to the Next Contact

This allows:
- Dynamic contact storage
- Efficient insertion and deletion
- Better memory utilization compared to fixed-size arrays

## 📸 Sample Output

```
1) Save a Contact
2) Delete a Contact
3) Display All Contacts
4) Search
0) Exit

Enter your choice: 1

Enter phone number: 9876543210
Enter Name: Venkatesh

Insertion successful
```

## 🎯 Learning Outcomes

- Implementation of Singly Linked List
- Dynamic Memory Management
- CRUD Operations in C
- Pointer Manipulation
- Menu-Driven Programming

## 🔮 Future Enhancements

- Update existing contacts
- Save contacts to a file
- Sort contacts alphabetically
- Search by phone number
- Password protection
- Graphical User Interface (GUI)

## 👨‍💻 Author

**T. Venkatesh**

B.Tech – Computer Science and Engineering

Vardhaman College of Engineering

## 📄 License

This project is developed for educational purposes.
