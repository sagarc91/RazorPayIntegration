# razorpay_payment

In App Payments using RazorPay

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

This is razorpay integration. Now start accepting customer's payment through various payment methods like cards, netbanking, wallets, upi

1. You have to add Razorpay Dependency : https://pub.dev/packages/razorpay_plugin#-readme-tab-

2. Create Account : Razorpay.com, go to settings to find API key

3. Add your key in startPayment method which is getting called on Make Payment button click

4. One small configuration change you have to do if you getting below error:
Error inflating class androidx.constraintlayout.widget.ConstraintLayout
Just go to module level build.gradle of razorpay project and replace:
implementation 'androidx.constraintlayout:constraintlayout:1.1.2'
to :
implementation 'androidx.constraintlayout:constraintlayout:1.1.3'

