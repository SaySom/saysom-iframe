# SaySom iFrame integration demo

See the files `normal.html` and `parameter.html` on how to integrate SaySom in your application. It is important to set the correct permission on the iframe for SaySom to be able to run.

## Parameters

`parameter.html` shows how to hand over the participant name automatically. The url is dynamic in that case, with the format of `https://web.saysom.app/{spaceId}?name=${name}`. The url parameters should be uri escaped.
