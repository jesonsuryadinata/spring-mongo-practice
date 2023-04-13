# spring-mongo-practice

## APIs :
>***GET***
#### 1. Get All Expenses
#### http://localhost:8080/api/expense

#### 2. Get Expense by Name
#### http://localhost:8080/api/expense/{name}

>***POST***
#### Add Expense
#### http://localhost:8080/api/expense
Request example :
```
{
"expenseName": "Netflix",
"expenseCategory": "ENTERTAINMENT",
"expenseAmount": 10
}
```
>***PUT***
#### Update Expense
`Before updating, use `[Get Expense by Name](#2-get-expense-by-name)` and copy the response.`
#### http://localhost:8080/api/expense
Request example :
```
{
    "id": "64366c214172d30d5626cfb9",
    "expenseName": "Netflix",
    "expenseCategory": "ENTERTAINMENT",
    "expenseAmount": 20
}
```
>***DELETE***
#### http://localhost:8080/api/expense/{id}