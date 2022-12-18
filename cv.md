# [rs-school](https://pierrepoint.github.io/rsschool-cv)
# Andrey Drapeza
### Contact
* Email:
Drapezoid@gmail.com
* [github](https://github.com/Pierrepoint)
* Discord:
Pierrepoint#4688
### About me
I'm a 6th year technical university student. I'm 23 years old and currently
obtaining knowledge in the field of front-end developments, as well as obtaining
master's degree from the university. I'm engaged in self-development, I'm fond of
reading books and watching movies. I take music very seriously. Lead a healthy lifestyle.
### Skills
* Engineering
* HTML/HTML5
* CSS3
* GIT
* JavaScript basics
### Strengths
* Responsible
* Purposeful
* Conscientious
* Attentive
* Capable
### Code Example
```const onLoaded = () => {
const storeTrackArray = localStorage.getItem("track_array");

if (storeTrackArray) {
const parsedTrackArray = JSON.parse(storeTrackArray);
parsedTrackArray.forEach(renderItem);
track_array = parsedTrackArray;
}
};

const removeElement = (name) => {
container.innerHTML = "";
track_array = track_array.filter((elem) => elem.name !== name);
localStorage.setItem("track_array", JSON.stringify(track_array));
track_array.forEach(renderItem);
};
```
### Education
* 2017-2021:
Bachelor's degree in Saint-Petersburg
Electrotechnical University
* 2021-2023(in process):
Master's degree in Saint-Petersburg
Electrotechnical University
* 2022-2023(in process):
RS School: JS/FE Pre-School
### Languages spoken
* English:
B1+ by EFSET
* Russian:
Native
* Belarusian:
Intermediate
