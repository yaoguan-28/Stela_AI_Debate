# Stela AI Debate Coach

Stela is an American-style debate AI opponent.
She always argues the opposite side, speaks only English, and uses logical evidence.

## API Info
API URL: https://api.coze.cn/v3/chat
Bot ID: 7634909367934320681

## How to use
Send a message: "Start"
Stela will begin the debate.

## Example Request
Headers:
Authorization: Bearer [Your Access Token]
Content-Type: application/json

Body:
{
  "bot_id": "7634909367934320681",
  "user_id": "user1",
  "content": "Start",
  "stream": false
}
