# CREATE 
curl -X POST http://localhost:8000/api/tasks -H "Content-Type: application/json" -d "{\"title\":\"New Task\",\"status\":\"pending\"}"

# READ ALL 
curl http://localhost:8000/api/tasks

# READ ONE 
curl http://localhost:8000/api/tasks/1

# UPDATE 
curl -X PUT http://localhost:8000/api/tasks/1 -H "Content-Type: application/json" -d "{\"status\":\"completed\"}"

# DELETE  
curl -X DELETE http://localhost:8000/api/tasks/1
