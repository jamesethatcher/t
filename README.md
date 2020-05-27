#service_name

This service allows users to...

## UML Diagram

[Mermaid](https://mermaidjs.github.io/)

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?

```

## Requirements

Install the requirements:

```

```

## Install

For the latest stable version:

```

```

## API

**Method**|**Pattern**|**Handler**|**Action**
:-----:|:-----:|:-----:|:-----:
| | |


## Examples

```apib
# GET /message
+ Response 200 (text/plain)

        Hello World!
```

## Testing

### Unit tests

Make sure the dependencies are installed:

```

```

Run the unit tests

```

```

Run the unit tests with a local server that supports the application requirements. Ensure that you run the tests from the root directory.

### Local testing

Build and run locally:
```

```

Build and run Docker container locally and forward traffic to a local port:

```
docker build -t service_name .
docker run -t -p 8080:8080 service_name
```

Navigate to localhost:8080 within a browser to view the application.

Alternatively, submit a request to test for a response:

```
curl -X GET 'http://localhost:8080/
```
