# Untitled string in TestResult Schema

```txt
https://platform.codeclimate.com/schemas/test-result#/properties/deletedAt
```

The time build was deleted.


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [TestResult.schema.json\*](../../spec/schemas/TestResult.schema.json "open original schema") |

## deletedAt Type

`string`

## deletedAt Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
