# /Drink

## `GET` /

**Request** ( N/A )

**Response** ( JSON )

- `[ ]`: Array
    - `id`: Int64
    - `icon`: Int32
    - `name`: String
    - `concentration`: Int16

## `GET` /:id

**Request** ( N/A )

**Response** ( JSON )

- `->`: Object
    - `id`: Int64
    - `icon`: Int32
    - `name`: String
    - `concentration`: Int16


## `POST` /

**Request** ( JSON )

- `->`: Object
    - `icon`: Int32
    - `name`: String
    - `concentration`: Int16

**Response** ( JSON )

- `->`: Object
    - `id`: Int64

## `PUT` /:id

**Request** ( JSON )

- `->`: Object
    - `id`: Int64
    - `icon`: Int32 ( optional )
    - `name`: String ( optional )
    - `concentration`: Int16 ( optional )

**Response** ( N/A )

## `DELETE` /:id

**Request** ( N/A )

**Response** ( N/A )
