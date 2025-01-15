---
title: Testing
---
Testing

<SwmSnippet path="/gradle-tests/espresso/accessibility/src/main/java/androidx/test/gradletests/espresso/accessibility/EspressoAccessibilityActivity.kt" line="2">

---

&nbsp;

```kotlin

import android.app.Activity
import android.content.Intent
import android.net.Uri
import android.os.Bundle
import android.view.View

class EspressoAccessibilityActivity : Activity(), View.OnClickListener {

  override fun onCreate(savedInstanceState: Bundle?) {
    super.onCreate(savedInstanceState)
    setContentView(R.layout.activity_espresso_accessibility)
  }

  override fun onClick(view: View) {
    val intent = Intent(Intent.ACTION_VIEW)
    intent.setData(Uri.parse("http://developer.android.com"))
    startActivity(intent)
  }
}

```

---

</SwmSnippet>

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBYW5kcm9pZC10ZXN0JTNBJTNBSWRpdFllZ2VyU3dpbW0=" repo-name="android-test"><sup>Powered by [Swimm](https://stag.swimm.cloud/)</sup></SwmMeta>
