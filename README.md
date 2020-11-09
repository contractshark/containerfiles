# CI Service Container Images

> Overview


### Supported tags and respective `Dockerfile` links

#{range $_, $v := .Versions}

#### #{$v.Version}

`#{range $_, $b := $v.Builds}`

 * `#{$b.Tag}`#{range $_, $t := $b.Base.AdditionalTags}, `#{$t}`#{end} [(#{$b.Base.Base}/Dockerfile)]($URL/#{$b.Base.Base}/Dockerfile)
#{end}#{end}


## License 

Apache-2.0
