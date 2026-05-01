**Infrastructure & Systems Developer** and a hobbyist who enjoys low level abstractions and making scalable applications

---

### Featured Projects

#### [Sweep](https://github.com/Bekfastbek/Sweep] (Work In Progress)
**Compiled Systems Language with zero cost memory safety without a borrow checker**
* Introduced a new concept called scope{} which acts as a lexical lifetime boundary where shared variables get promoted to the scope and owned variables gets RAII destruction
* First class SIMD and concurrency support using simd{} and spawn{}/merge{}
* Native vector and block functions without using macros
* Direct access to compiler using compiler{} which allows Lexer, AST, Sementics and IR while maintaining safety
* Raw access to the LLVM IR and access to Assembly 

#### [AnyArr](https://github.com/Bekfastbek/anyarr)
**Dynamic Arrays in C11 which can store multiple datatypes**
* The library is quick and powerful due to Virtual Arenas making alloc/dealloc a pointer bump and AVX512 where it's needed, beating the C++ stdlib 
* Great Type checking functions and using _Generic macro to infer the datatype allowing great DX
* It's a single file so it's awesome as a drop-in solution
#### [BareBot](https://github.com/Bekfastbek/BareBot)
**A custom Discord API implementation written in LibC and OpenSSL**
* Implemented manual socket handling and **Pthreads** for separation of listener and logic to prevent heartbeat skip
* Implemented custom HTTP/WSS client from scratch with only OpenSSL being the external library
* Future plans to eventually learn cryptography and replace OpenSSL TLS with my own TLS encryption
#### [Car Scraper](https://github.com/Bekfastbek/Car-Scraper)
**Asynchronous playwright scraper made in Python**
* Used playwright to scrape data from AutoEvolution.com since BS4 cannot work on javascript heavy webpages
* Scrapes about 1700 car models of every brand with every generation of their models with images
* Features a batching system optimized for multicore CPU architectures

---

### Skills

| Category           | Skills                                                                                                                         |
|:-------------------|:-------------------------------------------------------------------------------------------------------------------------------|
| **Languages**      | C/C++, Python, JavaScript & TypeScript, Golang, Java 21+                                                                       |
| **Low-Level**      | Pthreads, Win32 API, Inline x86 asm, x86 SIMD, LLVM                                                                            ||                    |                                                                                                                                |
| **Networking**     | VPNs (WireGuard, OpenVPN), HTTPS/WSS Client, TLS (OpenSSL)                                                                     |
| **Libraries**      | Playwright, FastAPI, DiscordAPI (discord.py & discord.js), Pillow & CV2                                                        |
| **Cloud**          | AWS (EC2, Fargate, S3, Lambda, Bedrock), GCP (Vertex AI, Virtual Machines), Azure (Virtual Machines), Digital Ocean (Droplets) |
| **Infrastructure** | Docker, Github Actions, Terraform, Prometheus, Grafana                                                                         |
| **Databases**      | PostgreSQL, MongoDB \| Amazon RDS and DynamoDB                                                                                                        |

---

### About Me
I am someone who enjoys learning about how modern computers work and I like making things from scratch since it gives me important insight on how each thing works.

I can do basically anything besides frontend (because I am bad at designing), feel free to reach out if you need help or have any questions I am always happy to help!
