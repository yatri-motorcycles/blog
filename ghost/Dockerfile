FROM ghost:4.48.9

WORKDIR /var/lib/ghost

RUN npm install ghost-storage-adapter-s3

RUN cp -vr ./node_modules/ghost-storage-adapter-s3 ./current/core/server/adapters/storage/s3