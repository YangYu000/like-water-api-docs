# /Record
## `GET` /

**Request** ( Query )

- `fromTime`: TimeStamp
- `toTime`: TimeStamp

**Response** ( JSON )

- `[ ]`: Array
    - `id`: Int64
    - `drinkId`: Int64
    - `time`: TimeStamp
    - `value`: Int32
    - `concentrationValue`: Int16

## `POST` /

**Request** ( JSON )

- `->`: Object
    - `drinkId`: Int64
    - `value`: Int32

**Response** ( JSON )

- `->`: Object
    - `id`: Int64

## `PUT` /:id

**Request** ( JSON )

- `->`: Array
    - `id`: Int64
    - `value`: Int32

**Response** ( N/A )