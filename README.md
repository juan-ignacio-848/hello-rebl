# hello-rebl

Update deps.edn to match your local environment.
Run clj :A:rebl:socket
Using Atom editor and chlorine, connect socket repl (localhost:50505)
and change something in hello_rebl.clj.

This warning should pop up: 

```clojure
{:ex #repl-tooling.editor-helpers.Browseable
  {:object #repl-tooling.editor-helpers.Error
    {:type java.io.FileNotFoundException,
     :message "Could not locate clojure/tools/namespace/repl__init.class, clojure/tools/namespace/repl.clj or clojure/tools/namespace/repl.cljc on classpath.",
     :add-data {},
     :trace [[clojure.lang.RT load "RT.java" 466]
             [clojure.lang.RT load "RT.java" 428]
             [clojure.core$load$fn__6824 invoke "core.clj" 6126]
             [clojure.core$load invokeStatic "core.clj" 6125]
             [clojure.core$load doInvoke "core.clj" 6109]
             [clojure.lang.RestFn invoke "RestFn.java" 408]
             [clojure.core$load_one invokeStatic "core.clj" 5908]
             [clojure.core$load_one invoke "core.clj" 5903]
             [clojure.core$load_lib$fn__6765 invoke "core.clj" 5948]
             [clojure.core$load_lib invokeStatic "core.clj" 5947]
             [clojure.core$load_lib doInvoke "core.clj" 5928]
             [clojure.lang.RestFn applyTo "RestFn.java" 142]
             [clojure.core$apply invokeStatic "core.clj" 667]
             [clojure.core$load_libs invokeStatic "core.clj" 5985]
             [clojure.core$load_libs doInvoke "core.clj" 5969]
             [clojure.lang.RestFn applyTo "RestFn.java" 137]
             [clojure.core$apply invokeStatic "core.clj" 667]
             [clojure.core$require invokeStatic "core.clj" 6007]
             [clojure.core$require doInvoke "core.clj" 6007]
             [clojure.lang.RestFn invoke "RestFn.java" 408]
             [hello_rebl$eval12806 invokeStatic "NO_SOURCE_PATH" 13]
             [hello_rebl$eval12806 invoke "NO_SOURCE_PATH" 13]
             [clojure.lang.Compiler eval "Compiler.java" 7176]
             [clojure.lang.Compiler eval "Compiler.java" 7165]
             [clojure.lang.Compiler eval "Compiler.java" 7166]
             [clojure.lang.Compiler eval "Compiler.java" 7131]
             [clojure.core$eval invokeStatic "core.clj" 3214]
             [clojure.core$eval invoke "core.clj" 3210]
             [unrepl.repl$LCGtW9Cgr88YHErE3u8GL_79IP4$start$interruptible_eval__12621$fn__12622$fn__12623$fn__12624 invoke "NO_SOURCE_FILE" 816]
             [unrepl.repl$LCGtW9Cgr88YHErE3u8GL_79IP4$start$interruptible_eval__12621$fn__12622$fn__12623 invoke "NO_SOURCE_FILE" 816]
             [clojure.lang.AFn applyToHelper "AFn.java" 152]
             [clojure.lang.AFn applyTo "AFn.java" 144]
             [clojure.core$apply invokeStatic "core.clj" 665]
             [clojure.core$with_bindings_STAR_ invokeStatic "core.clj" 1973]
             [clojure.core$with_bindings_STAR_ doInvoke "core.clj" 1973]
             [clojure.lang.RestFn invoke "RestFn.java" 425]
             [unrepl.repl$LCGtW9Cgr88YHErE3u8GL_79IP4$start$interruptible_eval__12621$fn__12622 invoke "NO_SOURCE_FILE" 808]
             [clojure.core$binding_conveyor_fn$fn__5739 invoke "core.clj" 2030]
             [clojure.lang.AFn call "AFn.java" 18]
             [java.util.concurrent.FutureTask run "FutureTask.java" 264]
             [java.util.concurrent.ThreadPoolExecutor runWorker "ThreadPoolExecutor.java" 1128]
             [java.util.concurrent.ThreadPoolExecutor$Worker run "ThreadPoolExecutor.java" 628]
             [java.lang.Thread run "Thread.java" 834], :more-fn (unrepl.repl$LCGtW9Cgr88YHErE3u8GL_79IP4/fetch :G__12808), :attributes nil, :phase :eval]}}}
```
