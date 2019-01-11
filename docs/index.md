# Like Waters API

## Route

* [Auth](auth)
* [User](user)
* [Drink](drink)
* [Record](record)
* [Award](award)

## Authorization
Every route except `Auth` require authorization.
Use `/Auth/Token` to retieve access token, and append "Authorization: Bearer access_token" HTTP header to access other APIs.

## DataTypes
| Name | BaseType | Description | Comment |
|---|---|---|---|
| Boolean |  | either `true` or `false` |  |
| Int16 |  | 16bit signed integral number |  |
| Int32 |  | 32bit signed integral number |  |
| Int64 |  | 64bit signed integral number |  |
| Double |  | 64bit double-precision floating point number |  |
| String |  | variable-length unicode characters |  |
| TimeStamp | Int64 | seconds elapsed since 1970/01/01 UTC | 1502439092 = 2017/08/11 16:11:32 UTC+8 |

