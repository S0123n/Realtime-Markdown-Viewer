str = str.replace(stra[0], '<a ' + 'href="' + stra[2] + '">' + stra[1] + '</a>');
+    if (stra[0].substr(0, 1) === '!') {
+        str = str.replace(stra[0], '<img src="' + stra[2] + '" alt="' + stra[1] + '" title="' + stra[1] + '" />\n');
+    } else {
+        str = str.replace(stra[0], '<a ' + 'href="' + stra[2] + '">' + stra[1] + '</a>');
+    }
[Elephorm](http://elephorm.com)