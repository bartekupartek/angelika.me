---
title: Test post sdf, title should be a little longer
description: Quisque porta cursus malesuada. Proin sed sapien felis. Pellentesque tristique rutrum nunc, ut volutpat massa vulputate eu. Fusce semper at leo at congue. In vel sapien condimentum, mattis nisi quis, cursus tortor. Nulla facilisi.
tags: [ruby, lifestyle, css]
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id sollicitudin mi, eu mollis orci. Pellentesque a justo nibh. Nulla congue lacus arcu, `at viverra nisl` condimentum ac. Etiam in sollicitudin neque. Morbi pellentesque enim magna, et eleifend ante consequat at. Sed mi risus, imperdiet eget laoreet sed, commodo quis risus. Praesent finibus ante nisl, id vehicula ipsum imperdiet eget. Nam vestibulum justo quis suscipit bibendum. Proin arcu urna, consequat non augue at, cursus sodales lacus. Quisque lacinia et nunc sit amet gravida. Vivamus consequat convallis risus et sagittis.

- List item 1
- List item 2
- List item 3
- List item 4

Phasellus *feugiat* ipsum **non dui** egestas dignissim. Nam consectetur elit ac vehicula posuere. Integer at metus at elit auctor tempor. Pellentesque ac diam dui. Morbi ante quam, sollicitudin eu posuere sed, placerat quis urna. Suspendisse potenti. Quisque ac sagittis ligula. Donec ac nunc at risus mollis feugiat eget ac nunc. Vivamus laoreet ex nec erat sollicitudin mollis. Quisque porta cursus malesuada. Proin sed sapien felis. Pellentesque tristique rutrum nunc, ut volutpat massa vulputate eu. Fusce semper at leo at congue. In vel sapien condimentum, mattis nisi quis, cursus tortor. Nulla facilisi.

Phasellus feugiat ipsum non dui egestas dignissim. Nam consectetur elit ac vehicula posuere. Integer at metus at elit auctor tempor. [I'm an inline-style link with title](https://www.google.com "Google's Homepage") Pellentesque ac diam dui. Morbi ante quam, sollicitudin eu posuere sed, placerat quis urna. Suspendisse potenti. Quisque ac sagittis ligula. Donec ac nunc at risus mollis feugiat eget ac nunc. Vivamus laoreet ex nec erat sollicitudin mollis. Quisque porta cursus malesuada. Proin sed sapien felis. Pellentesque tristique rutrum nunc, ut volutpat massa vulputate eu. Fusce semper at leo at congue. In vel sapien condimentum, mattis nisi quis, cursus tortor. Nulla facilisi.

## Second level header

In volutpat sem in est tristique finibus. Aenean blandit vitae velit eu egestas. In in ultricies dui. Nam quam quam, viverra porttitor est vitae, lacinia consectetur elit. In id semper elit. Mauris urna ligula, molestie euismod vulputate a, porttitor bibendum tortor. Praesent bibendum maximus cursus. Morbi ornare lobortis tortor, ac ullamcorper mauris fringilla sodales. Cras eget lectus suscipit, pharetra eros ut, rutrum ligula.

1. List item 1
    - Nested list item 1
    - Nested list item 2
2. List item 2
3. List item 3

Vivamus eu quam erat. Vestibulum imperdiet sapien a eros commodo, sed bibendum massa scelerisque. In nec auctor nulla, at efficitur libero. Nam iaculis ipsum magna, eu pharetra sem sollicitudin quis. Suspendisse eget risus at eros venenatis laoreet. Aliquam commodo, nunc ut fermentum accumsan, tortor arcu lacinia mauris, vel aliquet diam massa id ligula. Etiam ut malesuada ligula. Aliquam rutrum, nibh eget pretium venenatis, felis enim ultricies diam, eu ultrices enim tortor vel nibh. Cras orci dui, condimentum in mollis id, pulvinar vitae risus. Integer nisl est, varius in mauris sed, bibendum semper dolor.

```ruby
# This is a comment
class Complement
  COMPLEMENT = ->(nucleotide) { COMPLEMENTS[nucleotide] }
  COMPLEMENTS = {
    'G' => 'C',
    'C' => 'G',
    'T' => 'A',
    'A' => 'U'
  }

  class << self
    def of_dna(dna)
      unless valid_dna?(dna)
        raise ArgumentError, "#{ dna } is not a valid DNA strand."
      end
      
      x = 23 + 435
      y = 3.0 + 2.5
      z = :symbol
      regexp = /(\W)*/
      
      Complement::COMPLEMENTS

      dna.chars.map(&COMPLEMENT).join
    end

    private

    def valid_dna?(string)
      string.chars.all? { |char| COMPLEMENTS.keys.include?(char) }
    end
  end
end
```

### Third level header

Duis vitae erat nulla. Maecenas elementum, massa ac ullamcorper molestie, enim arcu tempus diam, et dignissim lorem purus eu nunc. Etiam nec tristique mauris, non lacinia tortor. Maecenas lectus nulla, tincidunt ut efficitur eu, faucibus nec velit. Vestibulum et velit sed ligula ullamcorper sodales. Curabitur lobortis ligula pharetra dictum laoreet. Integer mollis, libero eget pulvinar cursus, augue tortor tristique eros, vitae fringilla orci quam pretium lectus. In lobortis commodo arcu, non elementum ipsum volutpat et. Phasellus id rutrum enim. Sed suscipit, velit ac blandit ultrices, lectus massa blandit turpis, non aliquam mauris turpis sed nisi. Nulla placerat purus eros, vitae semper enim aliquet eget. 

#### Fourth level header

Duis vitae erat nulla. Maecenas elementum, massa ac ullamcorper molestie, enim arcu tempus diam, et dignissim lorem purus eu nunc. Etiam nec tristique mauris, non lacinia tortor. Maecenas lectus nulla, tincidunt ut efficitur eu, faucibus nec velit. Vestibulum et velit sed ligula ullamcorper sodales. Curabitur lobortis ligula pharetra dictum laoreet. Integer mollis, libero eget pulvinar cursus, augue tortor tristique eros, vitae fringilla orci quam pretium lectus. In lobortis commodo arcu, non elementum ipsum volutpat et. Phasellus id rutrum enim. Sed suscipit, velit ac blandit ultrices, lectus massa blandit turpis, non aliquam mauris turpis sed nisi. Nulla placerat purus eros, vitae semper enim aliquet eget. 

##### Fifth level header

Duis vitae erat nulla. Maecenas elementum, massa ac ullamcorper molestie, enim arcu tempus diam, et dignissim lorem purus eu nunc. Etiam nec tristique mauris, non lacinia tortor. Maecenas lectus nulla, tincidunt ut efficitur eu, faucibus nec velit. Vestibulum et velit sed ligula ullamcorper sodales. Curabitur lobortis ligula pharetra dictum laoreet. Integer mollis, libero eget pulvinar cursus, augue tortor tristique eros, vitae fringilla orci quam pretium lectus. In lobortis commodo arcu, non elementum ipsum volutpat et. Phasellus id rutrum enim. Sed suscipit, velit ac blandit ultrices, lectus massa blandit turpis, non aliquam mauris turpis sed nisi. Nulla placerat purus eros, vitae semper enim aliquet eget. 

##### Sixth level header

Duis vitae erat nulla. Maecenas elementum, massa ac ullamcorper molestie, enim arcu tempus diam, et dignissim lorem purus eu nunc. Etiam nec tristique mauris, non lacinia tortor. Maecenas lectus nulla, tincidunt ut efficitur eu, faucibus nec velit. Vestibulum et velit sed ligula ullamcorper sodales. Curabitur lobortis ligula pharetra dictum laoreet. Integer mollis, libero eget pulvinar cursus, augue tortor tristique eros, vitae fringilla orci quam pretium lectus. In lobortis commodo arcu, non elementum ipsum volutpat et. Phasellus id rutrum enim. Sed suscipit, velit ac blandit ultrices, lectus massa blandit turpis, non aliquam mauris turpis sed nisi. Nulla placerat purus eros, vitae semper enim aliquet eget. 