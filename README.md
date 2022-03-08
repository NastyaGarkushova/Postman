Postman hw_1

Создать запросы в Postman.
`Protocol: http://`  `IP: 162.55.220.72`  `Port: 5005`

/get_method
EP_1 `Method: GET`  `EndPoint: /get_method`

request url params: `name: str` `age: int`

response:

[
    "Pavel",
    "25"
]

/user_info_3
EP_2 `Method: POST`  `EndPoint: /user_info_3`

request form data: `name: str` `age: int`  `salary: int`

response:

{
	"name": "Anna",
	"age": "30",
	"salary": "80",
	"family": {
		"children": [
			["Alex", 24], 
			["Kate", 12]
        ],
		"u_salary_1_5_year": 320
	}
}
 
/object_info_1
EP_3 `Method: GET` `EndPoint: /object_info_1`

request url params: `name: str` `age: int` `weight: int`

response:

{
    "age": 20,
    "daily_food": 0.54,
    "daily_sleep": 112.5,
    "name": "Irina"
}

/object_info_2
EP_4 `Method: GET`  `EndPoint: /object_info_2`

request url params: `name: str` `age: int` `salary: int`

response:

{
    "person": {
        "u_age": 28,
        "u_name": [
            "Vlad",
            50,
            28
        ],
        "u_salary_5_years": 210.0
    },
    "qa_salary_after_1.5_year": 165.0,
    "qa_salary_after_12_months": 135.0,
    "qa_salary_after_3.5_years": 190.0,
    "qa_salary_after_6_months": 100,
    "start_qa_salary": 50
}


/object_info_3
EP_5 `Method: GET` `EndPoint: /object_info_3`

request url params: `name: str` `age: int` `salary: int`

response: json

{
    "age": "25",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "pets": {
            "cat": {
                "age": 3,
                "name": "Sunny"
            },
            "dog": {
                "age": 4,
                "name": "Luky"
            }
        },
        "u_salary_1_5_year": 400
    },
    "name": null,
    "salary": 100
}




/object_info_4
EP_6 `Method: GET`  `EndPoint: /object_info_4`

request url params: `name: str` `age: int` `salary: int`

response:

{
    "age": 30,
    "name": "Pavel",
    "salary": [
        100,
        "200",
        "300"
    ]
}


/user_info_2
EP_7 `Method: POST` `EndPoint: /user_info_2`

request form data: `name: str` `age: int` `salary: int`

response:

{
    "person": {
        "u_age": 28,
        "u_name": [
            "Vlad",
            50,
            28
        ],
        "u_salary_5_years": 210.0
    },
    "qa_salary_after_1.5_year": 165.0,
    "qa_salary_after_12_months": 135.0,
    "qa_salary_after_3.5_years": 190.0,
    "qa_salary_after_6_months": 100,
    "start_qa_salary": 50
}