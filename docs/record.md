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

## `POST` /

**Request** ( JSON )

- `->`: Object
    - `drinkId`: Int64
    - `value`: Int32,
    - `time`: Timestamp

**Response** ( JSON )

- `->`: Object
    - `id`: Int64

## `POST` /Multi

**Request** ( JSON )

- `[ ]`: Array
    - `drinkId`: Int64
    - `value`: Int32,
    - `time`: Timestamp