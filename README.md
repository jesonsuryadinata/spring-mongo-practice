# spring-mongo-practice

## APIs :
>#### 1. `GET` Get All Expenses http://localhost:8080/api/expense

>#### 2. `GET` Get Expense by Name http://localhost:8080/api/expense/{name}

>#### 3. `POST` Add Expense http://localhost:8080/api/expense
```json
// Request example :
{
"expenseName": "Netflix",
"expenseCategory": "ENTERTAINMENT",
"expenseAmount": 10
}
```

>#### 4. `PUT` Update Expense http://localhost:8080/api/expense
`Before updating, use `[Get Expense by Name](#2-get-expense-by-name)` and copy the response.`
Request example :
```json
{
    "id": "64366c214172d30d5626cfb9",
    "expenseName": "Netflix",
    "expenseCategory": "ENTERTAINMENT",
    "expenseAmount": 20
}
```

>#### 5. `DELETE` http://localhost:8080/api/expense/{id}