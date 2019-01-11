# /Auth

## `POST` /CheckExist
determine an Email already existed or not

**Request** ( JSON )

- `->`: Object
    - `email`: String

**Response** ( JSON )

- `->`: Object
    - `isExist`: Boolean

## `POST` /Register

**Request** ( JSON )

- `->`: Object
    - `email`: String

**Response** ( N/A )

## `POST` /Verify

**Request** ( JSON )

- `->`: Object
    - `email`: String
    - `code`: String

## `POST` /Token

**Request** ( JSON )

- `->`: Object
    - `email`: String
    - `password`: String

**Response** ( JSON )

- `->`: Object
    - `token`: String
    - `expiredAt`: Int64