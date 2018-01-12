# CardWidget
One line card input form ( Credit card number, Expiration Date, CVV, CID)

# How to Use.

Define view in layout (xml)
```sh
<com.devdigital.cardwidget.widget.CardInputWidget
        android:id="@+id/cardInput"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />
```
Access View in Java
```sh
CardInputWidget cardInputWidget = (CardInputWidget) findViewById(R.id.cardInput);
CardNumberEditText cardNumberEditText = cardInputWidget.getCardNumberEditText();
ExpiryDateEditText expiryDateEditText = cardInputWidget.getExpiryDateEditText();
```
