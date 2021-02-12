# NetworkLiveData
This is an example how to monitor Internet status changes with LiveData

- How to use

```sh
var cnnLiveData: NetworkLiveData = NetworkLiveData(context)
cnnLiveData.observe(viewLifecycleOwner) { _isOnline ->
    if (_isOnline) {
        // is online
    } else {
        // is offline
    }
}
```
