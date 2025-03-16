# js-random-lorem

```js
 function random_lorem_ipsum(x) {

    const lorems = ['Lorem ipsum dolor sit amet, consectetur adipiscing elit.', 'Suspendisse laoreet pretium quam, eget posuere libero tempor non.', 'Etiam scelerisque enim sed dui maximus fermentum.', 'Phasellus hendrerit arcu vel lobortis cursus.', 'Nullam vel facilisis erat, at sodales enim.', 'Integer tristique, nunc vel fringilla eleifend, nisl neque facilisis tortor, nec accumsan metus mi vitae erat.', 'Curabitur sit amet neque ligula.', 'Nullam eu rutrum quam, eget rutrum dolor.', 'Duis in consequat libero, sed sodales erat.', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.', 'In a convallis est.', 'Nulla ullamcorper lectus id dui sagittis condimentum.', 'Morbi ut dui sed metus fermentum blandit.', 'Vivamus id leo sed metus laoreet gravida in at est.', 'Vivamus condimentum erat ac ante ultrices lobortis.', 'Duis in sagittis purus, a aliquam mauris.', 'Integer venenatis, tellus ut pharetra imperdiet, elit lorem consequat nisi, in aliquam ante risus vitae nunc.', 'Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.', 'Duis fringilla interdum ex, et molestie massa vulputate volutpat.', 'Praesent hendrerit pulvinar ante, sit amet molestie dolor aliquet ac. Donec aliquam bibendum sem, nec auctor nisi blandit suscipit.', 'Suspendisse ut tellus nisl. Nullam massa nunc, iaculis in orci ut, ornare dignissim tortor.', 'Nunc congue libero ipsum, at dignissim turpis volutpat non.', 'In faucibus ex pellentesque, interdum enim eget, lacinia neque.', 'Pellentesque risus orci, malesuada eu consequat in, convallis eu diam.', 'Nam vel pellentesque mi, sed cursus velit.', 'Proin a lectus massa.', 'Mauris eleifend vehicula eleifend.', 'Integer quis nisi nibh.', 'Nam in bibendum elit, at sagittis est.', 'In quis ipsum non purus aliquam ultricies eu id erat.', 'Nulla ipsum ipsum, interdum sed malesuada et, sagittis quis nisl.', 'Vestibulum sodales in tortor nec congue.', 'Integer ut facilisis ante.', 'Phasellus hendrerit a leo quis fermentum.', 'Phasellus id nunc id risus dictum auctor.', 'Nulla varius est sit amet diam accumsan, sed viverra neque blandit.', 'Nam tristique enim id turpis aliquam malesuada.', 'Praesent eget ligula id ipsum porttitor finibus nec sed diam.', 'Vestibulum porttitor, metus eget facilisis dictum, elit eros tempor orci, vel pharetra elit justo a quam.', 'Aenean tempor tempor felis quis finibus.', 'Sed in nisi maximus, porttitor tortor eget, dignissim massa.', 'Vivamus aliquet vehicula risus, eu eleifend mi accumsan egestas.', 'Etiam luctus tempus leo pharetra elementum.', 'Suspendisse ac consectetur nulla.', 'Curabitur sed nisl magna.', 'Quisque ut fermentum odio.', 'Donec ut diam ac ante venenatis cursus.', 'In hac habitasse platea dictumst.', 'Nam accumsan rutrum nisl eu fringilla.', 'Etiam pulvinar in odio sed sagittis.', 'Mauris lobortis, nunc in elementum interdum, ante risus commodo justo, quis varius massa orci eu est.', 'Nunc et rhoncus purus, vel bibendum sem.', 'Cras mattis orci eget erat vulputate maximus.', 'Curabitur quis dolor mauris.', 'Pellentesque pharetra sapien ligula, vitae convallis odio suscipit eget.', 'Aliquam faucibus erat sed erat condimentum, sit amet convallis urna tincidunt.', 'In ut malesuada nibh, et hendrerit lectus.', 'In tristique, tortor faucibus pellentesque vestibulum, sem sem pretium erat, molestie interdum leo tellus ornare ex.', 'Nunc sapien mi, auctor a tortor sit amet, egestas sollicitudin orci.', 'Donec fermentum ut justo nec vulputate.', 'Integer a eros non ipsum dapibus volutpat.', 'Fusce in elit a risus tincidunt pulvinar ut sed libero.', 'Donec euismod, enim in commodo suscipit, sem massa tempor nisi, a posuere quam dolor vitae libero.'];
    const arr = []

    function dayRoll() {
        return lorems[Math.floor(Math.random() * lorems.length)];
    }

    for (let i = 0; i < x; i++) {
        arr.push(dayRoll());
    }

    if (x == null) {
        return dayRoll()
    }

    return arr.toString();
}

console.log(random_lorem_ipsum(20))
```

{{ site.data.element.license }}