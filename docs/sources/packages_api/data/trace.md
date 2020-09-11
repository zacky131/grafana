+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "Trace"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
+++

## Trace type

### Trace type

<b>Signature</b>

```typescript
export declare type Trace = TraceData & {
    duration: number;
    endTime: number;
    spans: TraceSpan[];
    startTime: number;
    traceName: string;
    services: Array<{
        name: string;
        numberOfSpans: number;
    }>;
};
```
<b>Import</b>

```typescript
import { Trace } from '@grafana/data';
```