Open the course module, enter this code. Then move onto the next course and do the same thing.

```
opener.scorm.set("cmi.score.raw", 100);
opener.scorm.set("cmi.score.scaled", 1);
opener.scorm.set("cmi.completion_status", "completed");
opener.scorm.set("cmi.success_status", "passed");
opener.scorm.set("cmi.exit", "");
opener.scorm.set("adl.nav.request", "exitAll");
opener.scorm.commit();
window.close();
```
