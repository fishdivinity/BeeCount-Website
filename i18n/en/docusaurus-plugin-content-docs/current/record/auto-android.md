---
sidebar_position: 4
---

# Android Auto Recording

Android supports multiple auto-recording methods: screenshot recognition and share recording.

## Method 1: Screenshot Recording

Take a screenshot after payment, and BeeCount automatically recognizes it.

### How to Use

1. Take a screenshot after completing payment
2. BeeCount detects the new screenshot
3. Automatically recognizes amount and merchant info
4. Confirmation dialog appears
5. Confirm to complete the record

### Enable Screenshot Listening

1. Open BeeCount
2. Go to "Me" > "Auto Recording"
3. Enable "Screenshot Auto Recognition"
4. Grant storage permission

### Supported Screenshot Types

- WeChat Pay success page
- Alipay payment success page
- Bank app transaction details
- Other payment receipt screenshots

## Method 2: Share Recording

Share payment information to BeeCount.

### How to Use

1. Find the transaction record in the payment app
2. Tap the "Share" button
3. Select "BeeCount"
4. Information is auto-recognized and filled in
5. Confirm to complete the record

### Supported Share Content

- Text (spending descriptions containing amounts)
- Images (payment screenshots)

## Recognition Capabilities

BeeCount uses AI to recognize:

- Amount
- Merchant name
- Expense category
- Notes

## Configuration Tips

### Best Practices

1. Enable screenshot recognition - Most stable and reliable
2. Grant necessary permissions - Storage permission
3. Add to whitelist - Prevent system from killing the app

### Power Saving

Screenshot recognition is passively triggered, only works when taking screenshots, no extra battery drain.

## FAQ

**Screenshot recognition not responding?**

1. Check if storage permission is granted
2. Check if screenshot listening is enabled
3. Try restarting the app

**Recognition results inaccurate?**

AI recognition may have errors. You can manually edit and save.

**Background app being killed?**

1. Add BeeCount to battery optimization whitelist
2. Allow background running
3. Lock the app in recent tasks
