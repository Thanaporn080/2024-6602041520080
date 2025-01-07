curl -X POST http://localhost:8080/api/auth/local/register \
      -H "Content-Type: application/json" \
      -H "Authorization: Bearer de8e7b3e47009100477f3bf6ea29b980bd80b67d0f2705b47859bebd160e37d176c071039e48d7faf7d1a8f7566473b88f2c262c9573d8334c7522ef92eb857f26654e52f7c666c7c0e594636cbd5c378273d6d3d9a77403fb96e7bab60edc85c40a89d0344ab34c0537df99716e1e2af5a2b34e96b14642deb25efa491ea1a9" \
      -d '{
            "username": "nam1234",
            "email": "nam123@hotmail.com",
            "password": "Name1234"
      }'
