### MyNotes

- Each service has own database
- Never enter to other service's database
- Each service run independently
- some services might function more efficiently with different types of DB's
- Data management is big challenge to all services
- communication strategies between services
    - Sync
        - using direct requests
    - Async
        - using events
        - event Bus flow
            - [Request<Signup>] => ServiceA [Emit<createAccount>] => Evnet Bus [Event<UserCreate>] => Service D [Handle<UserCreate>]

---
### References

* [Microservices with Node JS and React](https://www.udemy.com/course/microservices-with-node-js-and-react/)

