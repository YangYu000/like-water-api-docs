# /Auth
## `POST` /checkExist
determine an Email already existed or not

**Request** ( JSON )

- `->`: Object
    - `email`: String

**Response** ( JSON )

- `->`: Object
    - `isExist`: Boolean

## `POST` /register

**Request** ( JSON )

- `->`: Object
    - `email`: String
    - `password`: String

**Response** ( JSON )

- `->`: Object
    - `token`: String

## `POST` /token

**Request** ( JSON )

- `->`: Object
    - `email`: String
    - `password`: String

**Response** ( JSON )

- `->`: Object
    - `token`: String
    - `expiredAt`: Int64

## `POST` /refreshToken

**Request** ( JSON )

- `->`: Object
    - `token`: String

**Response** ( JSON )

- `->`: Object
    - `token`: String

## `POST` /forgetPassword
NOT IMPLEMENTED YET