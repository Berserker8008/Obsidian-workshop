
To denote a word or phrase as code, enclose it in back ticks (`` ` ``).
## For example:

To brew a perfect cup of tea, simply use the `brewTea()` function with parameters such as `'green'` for the type of tea, `'loose leaf'` for the tea leaves, `'80°C'` for the water temperature, and `'2 minutes'` for the steeping time.

# Code Blocks

To denote a code block in Obsidian MD, you can use triple backticks 

## For example

```rust
fn main() {
    let course_registration_bot = CourseRegistrationBot::new();

    match course_registration_bot.register_for_course("ICS343") {
        Ok(_) => println!("Course registration successful!"),
        Err(_) => println!("Error: Course registration failed. The registration system is busy. Try again later."),
    }
}

struct CourseRegistrationBot {}

impl CourseRegistrationBot {
    fn new() -> CourseRegistrationBot {
        CourseRegistrationBot {}
    }

    fn register_for_course(&self, course_name: &str) -> Result<(), ()> {
        Err(())
    }
}
```




