curl -X POST https://api.sandbox.midtrans.com/v2/charge \
  -H "Accept: application/json" \
  -H "Content-Type: application/json" \
  -u 'YOUR_SERVER_KEY:' \
  -d '{
    "payment_type": "qris",
    "transaction_details": {
      "order_id": "ORDER-123456",
      "gross_amount": 15000
    }
  }'
