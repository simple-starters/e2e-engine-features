# Rename Java Package Demo

This accelerator demonstrates how an accelerator author can use OpenRewrite to
rename Java packages in the generated content.

This accelerator returns a simple Spring Boot project. In the repo the root
package is called `com.renamethis`. 

The user can provide a value for the 'pkgName' option. The accelerator uses 
openrewrite to rename this package to the name specified by the user.
