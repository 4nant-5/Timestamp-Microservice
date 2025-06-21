# Timestamp Microservice API

A lightweight timestamp API built with **Node.js**, **Express**, and **MongoDB**. This service converts a given date string or UNIX timestamp into UNIX and UTC formats. It also logs each request to a MongoDB database.

## Features

- Convert date strings or UNIX timestamps to UTC and UNIX format
- Return current time if no date is given
- Handle invalid date inputs
- Log all requests in MongoDB (optional)

## Endpoints

### GET `/api/timestamp/`

Returns the current timestamp.

**Response:**
```json
{
  "unix": 1750464000000,
  "utc": "Sat, 21 Jun 2025 00:00:00 GMT"
}
