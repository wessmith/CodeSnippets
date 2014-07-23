#Xcode Snippets

This is my personal collection of Xcode snippets. It consists mostly of Specta snippets to make it easier to write specs by setting up the block for you. Rather than having to type out the syntax becuase the block parameter is defined as `id` (e.g. `it(NSString *name, id block)`) you get this:
```objc
    it(<#NSString *name#>, ^{
        <#code#>
    });
```
