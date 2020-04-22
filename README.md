# PermissionX
Android 运行时权限库

## 引入

```
dependencies {
    implementation 'com.chronglau.library:permissionx:1.0.0'
}

```

## 使用

```
PermissionX.request(this, Manifest.permission.CALL_PHONE) { allGranted, deniedList ->
    if (allGranted) {
        // call
    } else {
        Toast.makeText(this, "you denied the permission", Toast.LENGTH_SHORT).show()
    }
}

```


