# Consumer–Provider Handshake

## Thông tin chung

- Lab: FIT4110 Lab 03
- Ngày:
- Provider team:
- Consumer team:
- Provider service:
- Consumer service:
- Provider team: team-iot
- Consumer team: 
- Provider service: IoT Ingestion
- Consumer service: (fill by consumer)

## Contract

- Contract file:
- Mock base URL:
- Auth method:
- Endpoint được test:
- Contract file: contracts/iot-ingestion.openapi.yaml
- Mock base URL: http://localhost:4010
- Auth method: Bearer token in `Authorization` header
- Endpoint được test: POST /readings, GET /readings/latest

## Smoke test

### Request

```http
METHOD /path
Authorization: Bearer <token>
Content-Type: application/json
```

```json
{
}
```

### Expected response

```json
{
}
```

## Kết quả

- [ ] Consumer gọi mock thành công.
- [ ] Consumer parse được field cần dùng.
- [ ] Consumer hiểu lỗi 4xx/5xx provider trả về.
- [ ] Có Newman report hoặc screenshot.

## Ghi chú thay đổi hợp đồng

| Nội dung | Trước | Sau | Người đồng ý |
|---|---|---|---|
| | | | |

## Xác nhận

- Provider representative:
- Consumer representative:
- Provider representative: (name/email)
- Consumer representative: (name/email)
