# KeyDB

A simplified versioning, multiarch Docker image of the KeyDB project.



The dockerfiles in this repository are a mirror of the ones in Snap's official repository. With the OCI labels properly set.



You can check out Snap's repository at:
[GitHub - Snapchat/KeyDB: A Multithreaded Fork of Redis](https://github.com/Snapchat/KeyDB)



## Multiplatform driven

All the images in this repository are built for both ARM and AMD64.

## Image tagging strategy

Default linux is Alpine. A Bookworm variant is also available.

| Description    | OS       | Tag          |
| -------------- | -------- | ------------ |
| Latest release | Alpine   | latest       |
| Major version  | Alpine   | 6            |
| Major version  | Bookworm | 6-bookworm   |
| Minor version  | Alpine   | 6.3          |
| Minor version  | Bookworm | 6.3-bookworm |
