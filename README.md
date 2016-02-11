# Media

The Revolt `media` object places any image- and text-like content side-by-side.

## Dependencies

Revolt’s media object depends on three other of Revolt's modules:

* [settings.defaults](https://github.com/revolt-framework/settings.defaults)
* [tools.functions](https://github.com/revolt-framework/tools.functions)

## Usage

Basic usage of the Media object uses the required classes:

    <div class="o-media">
        <img class="o-media__figure" src="/path/to/image.png" alt="" />
        <div class="o-media__body">
            <p>Text-like content goes here.</p>
        </div>
    </div>

The only valid children of the `.o-media` node are `.o-media__figure` and
`.o-media__body`.

## Options

Other, optional classes can supplement the required base classes:

* `.o-media--flush`: remove the space between the image- and text-content.
* `.o-media--[tiny|small|large|huge]`: alter the spacing between the image- and
  text-content.
* `.o-media--reverse`: reverse the horizontal rendered order of the image- and
  text-content.

For example:

    <div class="o-media  o-media--flush  o-media--reverse">
        <img class="o-media__figure" src="/path/to/image.png" alt="" />
        <div class="o-media__body">
            <p>Text-like content goes here.</p>
        </div>
    </div>