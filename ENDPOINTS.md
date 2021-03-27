# Endpoints

- [User Endpoints](#user)
- [Band Endpoints](#band)
- [Show Endpoints](#show)

<a id="user"></a>
## ✦ User Endpoints

## **POST** Sign Up

**Path:** `/user/signup`

**Body:**

```json
{
    "name": "Astrodev",
    "email": "astro@dev.com",
    "password": "bestboss",
    "role": "ADMIN"
}
```
**Response:** token

## **POST** Login

**Path:** `/user/login`

**Body:**

```json
{
    "email": "dualipa@future.com",
    "password": "orgulhooms"
}
```
**Response:** token

---------------------

<a id="band"></a>
## ✦ Band Endpoints

## **POST** Register Band

**Path:** `/band/register`

**Headers**
```
authorization: token
```

**Body:**

```json
{
    "name": "Bananas in PJs",
    "genre": "Indie",
    "responsible": "Laranja"
}
```


## **GET** Band By Id or Name

**Path:** `/band`

**Query Param**: band's id/name

**Response:**

```json
{
    "id": "40dc5f96-4c46-4d6d-a26b-58df09806a1d",
    "name": "Taylor Swift",
    "genre": "Taylor Swift",
    "responsible": "Taylor Swift"
}
```
---------------------
<a id="show"></a>
## ✦ Show Endpoints

## **POST** Create Show

**Path:** `/show/create`

**Headers**
```
authorization: token
```

**Body:**

```json
{
    "bandId": "b988ee4a-55ee-45d5-8e1e-63b9606e5128",
    "weekDay": "Saturday",
    "startTime": 22,
    "endTime": 23
}
```


## **GET** Show By Day

**Path:** `/show`

**Query Param**: day (friday, saturday, sunday)

**Response:**

```json
{
    "result": [
        {
            "id": "14b4a2a3-ee79-404e-b38c-c4c4db2b007d",
            "weekDay": "SATURDAY",
            "startTime": 14,
            "endTime": 15,
            "bandId": "0a6728a8-424f-4aa4-923f-979d4f69c45a"
        },
        {
            "id": "d2491c8d-4d46-43c1-a2c5-3437c196bf68",
            "weekDay": "SATURDAY",
            "startTime": 16,
            "endTime": 18,
            "bandId": "40dc5f96-4c46-4d6d-a26b-58df09806a1d"
        },
        {
            "id": "fb154c33-9ac4-4be7-8439-d945398383df",
            "weekDay": "SATURDAY",
            "startTime": 19,
            "endTime": 20,
            "bandId": "61c4aae5-01fa-4282-bc3d-226fbc4e9df8"
        },
        {
            "id": "15c1ac4c-a9d8-40b4-aa64-24e623e255ce",
            "weekDay": "SATURDAY",
            "startTime": 20,
            "endTime": 21,
            "bandId": "7f678d03-3370-42f4-bd99-8d682dc2fa3e"
        },
        {
            "id": "d8642a51-2c38-4a1c-93ab-99a27ba106f0",
            "weekDay": "SATURDAY",
            "startTime": 22,
            "endTime": 23,
            "bandId": "b988ee4a-55ee-45d5-8e1e-63b9606e5128"
        }
    ]
}
```