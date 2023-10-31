# Fuzzers

Статья про построение фермы для фаззинга: [https://habr.com/ru/company/dsec/blog/517596/](https://habr.com/ru/company/dsec/blog/517596/)

Dockerfiles for some fuzzers: [https://github.com/WiseSecurity/dockerized-fuzzers](https://github.com/WiseSecurity/dockerized-fuzzers)

WEIZZ: Automatic Grey-Box Fuzzing for Structured Binary Formats\
Slides: [https://andreafioraldi.github.io/assets/weizz-issta2020-slides.pdf](https://andreafioraldi.github.io/assets/weizz-issta2020-slides.pdf) \
Video: [https://www.youtube.com/watch?v=MOeUqlFtgwE](https://www.youtube.com/watch?v=MOeUqlFtgwE) \
Article: [https://andreafioraldi.github.io/assets/weizz-issta2020.pdf](https://andreafioraldi.github.io/assets/weizz-issta2020.pdf) \
Code: [https://github.com/andreafioraldi/weizz-fuzzer](https://github.com/andreafioraldi/weizz-fuzzer)

Fuzzing JavaScript Engines with Aspect-preserving Mutatio[ https://github.com/sslab-gatech/DIE](https://github.com/sslab-gatech/DIE)

Storm - a blackbox mutational fuzzer for detecting critical bugs in SMT solvers Article: [https://numairmansur.github.io/STORM.pdf](https://numairmansur.github.io/STORM.pdf) Code: [https://github.com/Practical-Formal-Methods/storm](https://github.com/Practical-Formal-Methods/storm)

UAFuzz: Binary-level Directed Fuzzing for Use-After-Free Vulnerabilities [https://github.com/strongcourage/uafuzz](https://github.com/strongcourage/uafuzz)

radamsa [https://gitlab.com/akihe/radamsa](https://gitlab.com/akihe/radamsa) создание мутаций из примеров\
Например:&#x20;

```
# Generate 1000 example payloads
radamsa -n 1000 -o %n.txt example1.txt example2.txt
```

FLUFFI - фреймворк для "пентестров" для фаззинга бинарей [https://github.com/siemens/fluffi](https://github.com/siemens/fluffi)

Что специалисты из NCC Group использовали для фаззинга 5g protocols: [https://research.nccgroup.com/2021/10/11/the-challenges-of-fuzzing-5g-protocols/](https://research.nccgroup.com/2021/10/11/the-challenges-of-fuzzing-5g-protocols/)

ClusterFuzz — ферма фаззинга от Google

OneFuzz — ферма фаззинга от Microsoft
