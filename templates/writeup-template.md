# <Lab Name> — Detailed Writeup  
Date: <YYYY-MM-DD>  
Source: PortSwigger — <lab id or title>

---

## Summary  
<Short summary of the vulnerability and what the lab demonstrated.>

---

## Target & Scope  
- Target: example.com (PortSwigger lab)  
- Endpoint(s) tested: <list>  
- Authentication: <required/not required>  
- Public writeup allowed: Yes  

---

## Steps to Reproduce (Sanitized)

### 1. Initial Request
```
<Sanitized HTTP request here>
```

### 2. Observed Response  
```
<Sanitized response / relevant JSON fields>
```

### 3. Modification / Exploitation  
<Explain what changed: ID, param, header, token, etc.>

### 4. Result  
<Explain what happened and why it’s a vulnerability.>

---

## Proof of Concept (curl example)
```
curl -s -X <METHOD> 'https://example.com/<endpoint>' \
  -H 'Authorization: Bearer <REDACTED>' \
  -H 'Content-Type: application/json'
```

---

## Screenshots  
(Stored in `/screenshots/<lab-folder>/`)  
- 01-request.png  
- 02-exploit.png  
- 03-result.png  

---

## Root Cause  
<Short explanation why the vulnerability exists.>

---

## Mitigation  
<Short list of recommended fixes: server-side checks, validation, etc.>

---

## References  
- OWASP: <related vulnerability>  
- PortSwigger: <related article>

