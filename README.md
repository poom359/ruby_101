# Ruby 101
steps on learning Ruby for Rails

## Getting Started
Install rbenv: https://github.com/rbenv/rbenv

## Index
### Introduction
```
$ ruby --version
ruby 3.3.4 (2024-07-09 revision be1089c8ec) [arm64-darwin23]
```
```
$ ruby
puts "Hello World"
^D
Hello World
```
```
$ irb
irb(main):001> puts "Hello World"
Hello World
=> nil
irb(main):002* def sum3(x, y, z)
irb(main):003*   x + y + z
irb(main):004> end
=> :sum3
irb(main):005> sum3(1, 2, 3)
=> 6
```

### Basic Syntax
```
$ ruby myprog.rb
Hello, World!
It is 2024-09-11 13:10:05 +0700
```

```
$ chmod +x shebang.rb
$ ./shebang.rb
Hello, World!
It is 2024-09-11 13:15:16 +0700
```

Ruby is a pure object-oriented language with no basic types.
```
$ ruby puts_example.rb
9
2
true
I'm playing gin joint
```

```
$ ruby hello.rb
Hello, Rick, and Goodbye!
Hello, Lori, and Goodbye!
main
Object
```

Practice time, write a ruby code which will give output like this:
```
$ ruby practice.rb
Hello World!
Good morning! Mac
```

### Methods
#### Method Name
#### super
### Array and Hash
### Symbols
### Control Structure
### Statement Modifier
### Blocks
### Commenting Ruby
### Classes and Objects
#### Objects and Attributes
#### Access Control
### Proc and Lambda
#### Passing block arguments
### Enumerator
