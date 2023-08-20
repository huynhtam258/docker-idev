chạy docker backend
docker compose up -d 

cập nhật node 
docker compose build node 
docker compose up node -d

cập nhật mongodb
docker compose build mongo
docker compose up mongo -d