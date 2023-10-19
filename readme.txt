curl -X 'POST' \
  'http://localhost:8088/api/v1/auth/register' \
  -H 'accept: */*' \
  -H 'Content-Type: application/json' \
  -d '{
  "firstname": "art",
  "lastname": "van",
  "email": "artvan@gmail.com",
  "password": "art123",
  "address": "string",
  "mobileNumber": "string",
  "gender": "MALE",
  "role": "USER"
}'