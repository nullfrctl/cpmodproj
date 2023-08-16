<!-- @format -->

# cpmodproj content templates <img align="right" src="https://user-images.githubusercontent.com/99456326/253195160-df589079-e508-4c30-8bd4-f7acebc43187.svg" width="32px">

<sup>REDmodding template repository.</sup>

Numerous templates for different options to format and license your works based on **[cpmodproj]**.

## Usage

There are many ways modders can use [cpmodproj], but, this focuses on the main ways that modders license their works:

1. allowing derivative works as long as you (the creator) is credited;
1. entirely disallowing any derivative works&mdash;unless given permission from you (&mdash;and only from you).

### Choosing your license

1. If you want your mod to be shared in a non-commercial manner, but allowing derivative works (e.g. unpacking and/or modifying source files) to be made; copy **[LICENSE.md](ShareAlike/LICENSE.md)** as well as **[README.md](ShareAlike/README.md)** from the **[ShareAlike](ShareAlike/)** folder.
1. Subsequently, if you want your mod to be shared in a non-commercial manner, but explicitly **disallowing** derivative works of any kind&mdash;except if they had explicit permission from you (which should entail proper credit)&mdash;copy **[LICENSE.md](NoDerivatives/LICENSE.md)** as well as **[README.md](NoDerivatives/README.md)** from the **[NoDerivatives](NoDerivatives/)** folder.

After you've chosen your license&mdash;either ShareAlike (option 1) or NoDerivatives (option 2)&mdash;edit the README.md you chose to fit your mod.

Either README.md file has in-depth explanations on how to edit them to fit you.

### Formatting

#### Links

- Try only inserting text in brackets for links. For example, instead of writing `[WolvenKit](https://github.com/WolvenKit/WolvenKit)`, try to simply write `[WolvenKit]`, then at the end of the document, write `[WolvenKit]: https://github.com/WolvenKit/WolvenKit`.
- Bold every link. This is very convenient when paired with the first rule&mdash;you can simply write `**[WolvenKit]**` to get a link according to the format.

#### Headings

- If the headings can have some contextual images, try to add them as `<img>` tags and `align="right"` them. You can see this effect with the top level heading of, and the license heading below.
- This is totally personal preference, but try to make your headings capitalized in only sentence-case. "Choosing your license" looks and feels more natural than "Choosing Your License".
- Make sure to only have one top level heading. You should have no more than the title (e.g. `# cpmodproj`) as a top level heading.

#### Images

- They should be under `<img>` tags and at most 480px wide.

#### Special characters

- Use HTML entities rather than Unicode characters or imitations of them (e.g. &mdash; instead of --; and &hellip; instead of ...) whenever possible.
- The em-dash (&mdash;) and en-dash (&ndash;)&mdash;which shall not be confused with a hyphen-minus (-)&mdash;should be used when it fits, as well as without any spacing.
- Examples:
  + **Right**  
    _Jane&mdash;however&mdash;did something no-one else thought they could do: become a Nobel Prize&ndash;winning scientist&hellip;_
  + **Wrong**  
    _Jane -- however -- did something no-one else thought they could do: become a Nobel Prize-winning scientist..._

#### Credits

- When you write credits under the **_License and credits_** heading, it should be under the **_Credits_** subheading.
- Furthermore, format it as a list, having the modder's name without a link. After the plain text name, add hyperlinked icons for where you can find them. (example below)
  - **nullfractal (Santiago Velasquez)** <sub>[<img src="https://images.nexusmods.com/favicons/ReskinOrange/favicon-230x230.png" height="16px">](https://www.nexusmods.com/cyberpunk2077/users/75442863) [<img src="https://github.com/fluidicon.png" height="16px">](https://github.com/nullfrctl)</sub>  
    <sup>for making **[cpmodproj]**&mdash;**[xtaltha]**</sup>

## License [<img align="right" height="16px" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg"><img align="right" height="16px" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg"> <img align="right" height="16px" src="https://mirrors.creativecommons.org/presskit/icons/by.svg"> <img align="right" height="16px" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg">][CC BY-NC-SA 4.0]

**[cpmodproj]** © 2023 by **[xtaltha]** is licensed under **[CC BY-NC-SA 4.0]**

_This is an unofficial fan work and is not approved/endorsed by CD PROJEKT RED._

[CC BY-NC-SA 4.0]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[xtaltha]: https://github.com/xtaltha
[cpmodproj]: https://github.com/xtaltha/cpmodproj
