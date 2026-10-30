``` rs
struct Rei;

impl Rei {
    fn life() -> (&'static str, u8) {
        let info = ("Rei", 18);
        info
    }

    fn contacts() -> [&'static str; 2] {
        let contacts = ["Telegram: @tonyqarri", "Discord: kzbv"];
        contacts
    }

    fn language() -> [&'static str; 2] {
        let langs = ["Python", "Rust"];
        langs
    }

    fn code_editor() -> &'static str {
        let editor = "Vs Code";
        editor
    }

    fn specialities() -> [&'static str; 2] {
        let skills = ["Automation", "Reverse Engineering (learning)"];
        skills
    }
}

fn main() {
    println!("Life {:?}", Rei::life());
    println!("Contacts: {:?}", Rei::contacts());
    println!("Languages: {:?}", Rei::language());
    println!("CodeEditor: {:?}", Rei::code_editor());
    println!("Specialities: {:?}", Rei::specialities());
}
```
