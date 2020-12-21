---
layout: page
title: Databank API
permalink: /api/
---
# Databank API

## Introduction

## Endpoint list

### `GET /commodities`

Returns the list of all known commodities.

* Supports filtering: **yes**
* Supports sorting: **yes**
* Supports pagination: **yes**

### `GET /commodities/:id`

Returns information about a commodity.

* Supports filtering: **no**
* Supports sorting: **no**
* Supports pagination: **no**

### `GET /stations`

Returns the list of all known stations.

* Supports filtering: **yes**
* Supports sorting: **yes**
* Supports pagination: **yes**

### `GET /stations/:id`

Returns information about a station.

* Supports filtering: **no**
* Supports sorting: **no**
* Supports pagination: **no**

### `GET /stations/:id/commodities`

Returns the list of commodities available or provided in a station.

* Supports filtering: **yes**
* Supports sorting: **yes**
* Supports pagination: **yes**

### `GET /stations/:id/commodities/:id`

Returns information about a commodity available or provided in a station.

* Supports filtering: **no**
* Supports sorting: **no**
* Supports pagination: **no**
