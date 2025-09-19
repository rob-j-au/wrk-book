node worker.js --wtype wrk-book-rack --env development --debug true --rack 25d0c2e5-3d14-4975-bddf-b836bdf3842a

docker build -t wrk-book .

docker run wrk-book worker.js --wtype wrk-book-rack --env development --debug true --rack 25d0c2e5-3d14-4975-bddf-b836bdf3842a