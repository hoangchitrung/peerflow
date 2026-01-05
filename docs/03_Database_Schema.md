## Collections `users`
- `uid`: String (Primary key from Firebase Auth)
- `username`: String
- `email`: String
- `avatar`: String (Link to the image)
- `bio`: String (Short introduction)
- `status:` String (online/offline)
- `created_at`: Timestamp
## Collections `conversations`
- `conversation_id`: String
- `participants`: Array (Contains UID of participants of the conversations)
- `last_message`: String (Last message show up in the conversation list)
- `updateAt`: Timestamp (Last time message)
## Collections `messages`
- `message_id`: String
- `sender_id`: String
- `receiver_id`: String
- `type`: String (`text`| `file`)
- `status`: String (`sent`|`seen`)
- `timestamp`: Timestamp
## Collections `file`
- `file_metadata`: Map
- `file_name`: String
- `url`: String
- `size`: Number (bytes)
- `expiry_at`: Timestamp
- `is_deleted_from_server`: Boolean (default is false)