# /User

## `POST` /Password

**Request** ( JSON )

- `->`: Object
    - `password`: String

**Response** ( N/A )

## `GET` /

**Request** ( N/A )

**Response** ( JSON )

- `->`: Object
    - `id`: Int64
    - `email`: String

## `PUT` /

**Request** ( JSON )

- `->`: Object
    - `Birthday`: Timestamp ( optional )
    - `Weekdays`: String ( optional )
    - `Gender`: Int32 ( optional )
    - `Weight`: Double ( optional )
    - `Height`: Double ( optional )

**Response** ( N/A )
