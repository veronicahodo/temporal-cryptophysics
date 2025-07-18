```
{
  previous_hash: '',
  protocol: 'v1',
  scope: '',
  nonce: '5nCDu6s7hkkjoxQ8NwxxMiXT_iOuHF-xdHl-UtIuXus',
  record_type: 'genesis',
  data: {
    name: 'Trust Architect Core',
    key: 'hFi1tUR5BeBotpWrEtAomSfnNtL_kvIXWhfaPZ5jyDk',
    js_at: 1752861608782
  },
  signatures: [
    {
      fingerprint: 'hFi1tUR5BeBotpWrEtAomSfnNtL_kvIXWhfaPZ5jyDk',
      type: 'owner',
      signature: 'YjaSmYnVdcY8PEBrVvnCQ7K7QHlhNtMvn2zCVFD9ZzppCtF6KFlsMCP_kjztJUv1fHFhv-hNgzkzhenewyiNDA'
    },
    {
      fingerprint: 'hFi1tUR5BeBotpWrEtAomSfnNtL_kvIXWhfaPZ5jyDk',
      signature: 'HG-_JJBq-K8rmIiSnO2vn5YfGHgLAoymwG1d1i5xpVjCTgVwO0Ds4t0ms_EkoflgduZIX_thEMDRM-q-EPHwBg',
      type: 'usher'
    }
  ],
  at: '0',
  current_hash: '3Ez2dtgOW3MrkYMd1BOBWeE9bZ1b6rZtM6K7kmFSXQo='
}
```

---

```
{
  previous_hash: '3Ez2dtgOW3MrkYMd1BOBWeE9bZ1b6rZtM6K7kmFSXQo=',
  protocol: 'v1',
  scope: '',
  nonce: 'pdNYu3bj01p24YhiEgbFZjIEH_DrKy0PL18dNla-0x0',
  record_type: 'policy:set',
  data: {
    schema: 'policy.set/1',
    write: [ 'core', 'root' ],
    read: [ 'any' ],
    mirror: [ 'any' ],
    grant: [ 'core', 'root' ],
    revoke: [ 'core', 'root' ],
    allow_records: [ 'scope:*', 'core:*' ],
    deny_records: [ 'all' ],
    quorum: { write: 1, grant: 1, revoke: 2 }
  },
  signatures: [
    {
      fingerprint: 'hFi1tUR5BeBotpWrEtAomSfnNtL_kvIXWhfaPZ5jyDk',
      type: 'owner',
      signature: 'SZCOY8h_bfZMYnfgkVioauSUhSzTmMl-4WEpjPA60bM6envPWspV8GXTRModkUzGo09mM5RQhZMYJcSXfC3vCA'
    },
    {
      fingerprint: 'hFi1tUR5BeBotpWrEtAomSfnNtL_kvIXWhfaPZ5jyDk',
      signature: 'T48fWxMALZ5aIz_Qu54r3HwedDnsvfMo4cQOhPUuTmx31f2CmDIYm6mTJUlnKXwsfwKMzp337PWuXmczTlIlBA',
      type: 'usher'
    }
  ],
  at: '69',
  current_hash: '/RKtDP4RMLxCWdGUDKWT1eyIN7+hI8d/0KQmrAiEfAA='
}
```

---

```
{
  previous_hash: '/RKtDP4RMLxCWdGUDKWT1eyIN7+hI8d/0KQmrAiEfAA=',
  protocol: 'v1',
  scope: '',
  nonce: 'qY9UWqdmwDONd1GR9-Dw2nYtiATVTOSSU3f9zA07SfI',
  record_type: 'key:grant',
  data: {
    schema: 'key.grant/1',
    name: 'Trust Architect Keymaster',
    key: 'SVlWU1Z4bEhpYkxWcGNsc1FoNDdxWWZXdDVMaFlOVnNRSGFIb2ViMnJFOA'
  },
  signatures: [
    {
      fingerprint: 'hFi1tUR5BeBotpWrEtAomSfnNtL_kvIXWhfaPZ5jyDk',
      type: 'owner',
      signature: '9j6Vo_2r38lzhXzn-i0444aVlGV2LX4tM5tpMw-p-KA2j-8d-nIcoVMNSNoOPs5gkVBpDrl63q0AD95LwaEjAw'
    },
    {
      fingerprint: 'hFi1tUR5BeBotpWrEtAomSfnNtL_kvIXWhfaPZ5jyDk',
      signature: 'euPsW1SLKzDswHvKZUUFDVPa65Btxs4TktVDBO5xD8ClK_QfOwSaP69BmAWym_Q7J4rCTworWQshMjn9EtmLAw',
      type: 'usher'
    }
  ],
  at: '104',
  current_hash: 'rxN15XxfRxf9LgjlnosS3Z5Vg+5UG4m2u0NS5VmhfQQ='
}
```

---

```
{
  previous_hash: 'rxN15XxfRxf9LgjlnosS3Z5Vg+5UG4m2u0NS5VmhfQQ=',
  protocol: 'v1',
  scope: '',
  nonce: 'vHMNiIwaiWnO-_2rekU_bNsg8cdIpMIPY8KYdCZAIFw',
  record_type: 'scope:create',
  data: {
    schema: 'scope.create/1',
    scope: 'self',
    description: 'Scope for sovereign identities',
    ushers: [
      { ipAddress: '34.71.60.51', port: 1984 },
      { ipAddress: '34.71.60.51', port: 3000 },
      { ipAddress: '34.71.60.51', port: 3001 },
      { ipAddress: '34.71.60.51', port: 3002 },
      { ipAddress: '34.71.60.51', port: 3003 }
    ],
    keys: {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      roles: [ 'authority', 'quorum' ]
    },
    created_at: 'GT[0.000000116]',
    created_by: 'Trust Architect Core'
  },
  signatures: [
    {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      type: 'owner',
      signature: 'P0aAsqrcmuft-c55_cNy6zdxC8ccNWjzuulcBBFplZecJD5UgQQnJyG0f5SaofajETwGTzgE-fottnA5_S1QCg'
    },
    {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      signature: 'G_g0Nd-PHv_snPZEKI4mFeEAbNxreQCICrnzDGpfgaW9QE47G5OKIZKQmEmRAGEGkzIORMu9QawC7jHD6r09Cw',
      type: 'usher'
    }
  ],
  at: '127',
  current_hash: 'xmeCQqtORmcbjjBqbVHzrzmvRLYYRdakcDlXYWjz1UQ='
}
```

---

```
{
  previous_hash: 'xmeCQqtORmcbjjBqbVHzrzmvRLYYRdakcDlXYWjz1UQ=',
  protocol: 'v1',
  scope: 'self',
  nonce: 'sqG3OF0vBh4nQMHnGZJKnO6scqNJv-PII3HOy2YhxOM',
  record_type: 'scope:genesis',
  data: {
    schema: 'scope.genesis/1',
    keys: {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      roles: [ 'authority', 'quorum' ]
    }
  },
  signatures: [
    {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      type: 'owner',
      signature: 'y-ChbR88nj9OQdk-3ALxaADHgQl4oBCfr984yyZRs9JGWr7IlpS1T7Iag03UFb8pGK8cr2SynazM0cpc0AgiBw'
    },
    {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      signature: 'F0c5bT8WvayflRR5iIM5s5bQBfbLp6HjCzDBqJS5UOZaKVNDE85yyn0HcnnE44HOG0VLkUFuFClnzJiIUhjVAg',
      type: 'usher'
    }
  ],
  at: '162',
  current_hash: 'XVHgmG06xD7QsovHf+W2FN1/BpUkFCtwrvTLRpisZwo='
}
```

---

```
{
  previous_hash: '',
  protocol: 'v1',
  scope: 'self',
  nonce: 'rNIk0cFLDPGlrF8M1OhVkMRiE2HZY38_U3JHxPnBWvY',
  record_type: 'scope:create',
  data: {
    schema: 'scope.create/1',
    scope: 'self.0000-0000-0000-0000',
    description: 'Scope for SelfID 0000-0000-0000-0000',
    ushers: [
      { ipAddress: '34.71.60.51', port: 1984 },
      { ipAddress: '34.71.60.51', port: 3000 },
      { ipAddress: '34.71.60.51', port: 3001 },
      { ipAddress: '34.71.60.51', port: 3002 },
      { ipAddress: '34.71.60.51', port: 3003 }
    ],
    keys: [
      {
        fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
        roles: [ 'authority', 'quorum' ]
      }
    ],
    created_at: 'GT[0.000000185]',
    created_by: 'Veronica Hodo <0000-0000-0000-0000>'
  },
  signatures: [
    {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      type: 'owner',
      signature: 'rPip_GB_fWGeX36vTMepl-QZ2fSbej4DnSnxOXS0MuIeYcekSmpy58Ui6OLi3ecz1XHPbEqMrJ9QdmsNQ_YYAA'
    },
    {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      signature: 'R8dEOGi-vNAVCEA6cTxyzMEBErR4PxjylLU5s2Qq4gn219h5gTkscg-EE72p7_vvi6oN7jbIDZT9kACa4pDdDg',
      type: 'usher'
    }
  ],
  at: '197',
  current_hash: 'KweS1aU2KnFFq8aGqQzhL839v31Sq/zTmOWkNMz4bqQ='
}
```

---

```
{
  previous_hash: 'KweS1aU2KnFFq8aGqQzhL839v31Sq/zTmOWkNMz4bqQ=',
  protocol: 'v1',
  scope: 'self',
  nonce: 'GFZyXGgkwoIUqd4FVr7mjhwU7GVMLxubXa9YfotXeJg',
  record_type: 'policy:set',
  data: {
    schema: 'policy.set/1',
    write: [ 'authority', 'owner' ],
    read: [ 'any' ],
    mirror: [ 'any' ],
    grant: [ 'authority', 'owner' ],
    revoke: [ 'authority', 'owner' ],
    allow_records: [ 'identity:*', 'scope:*', 'assert:*' ],
    deny_records: [ 'all' ],
    quorum: { write: 1, grant: 1, revoke: 2 }
  },
  signatures: [
    {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      type: 'owner',
      signature: 'PuqWIjmNPzUBP-ioymFHrF03GXYle-1BRAH0pot7qLIZsECJNYdz-f0uMwTjBqUjX5UzFkKyj0O2X8Zfp9I-CA'
    },
    {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      signature: '4iW7eUYUR5OD9sa2VhoAspEztjVUox59EfYFBaa02qlDuCStTGLffdZTIMkNP7gCCavpKw9JYPOS54wKxJ6IBA',
      type: 'usher'
    }
  ],
  at: '208',
  current_hash: 'lzmEj8rLA45ChPrlPxZK8SaE9zZScmXD4iUYJT012OQ='
}
```

---

```
{
  previous_hash: 'lzmEj8rLA45ChPrlPxZK8SaE9zZScmXD4iUYJT012OQ=',
  protocol: 'v1',
  scope: 'self',
  nonce: 'hxhpjlzaWafMq-AejpuX8kiyi7jHk9sAlZGf_ewKGco',
  record_type: 'identity:claim',
  data: {
    schema: 'identity.claim/1',
    name_given: 'Veronica',
    name_family: 'Hodo',
    name_display: 'Veronica Hodo',
    at: 'GT[0.000000232]'
  },
  signatures: [
    {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      type: 'owner',
      signature: 'aV7jou982Kj41u1MotmRaVE6ziXhGqleEZhWbVfBYriaGUuR3U65EPFIR9vY-X00W9JfK_ixq9HnioZbeuoQCg'
    },
    {
      fingerprint: 'IYVSVxlHibLVpclsQh47qYfWt5LhYNVsQHaHoeb2rE8',
      signature: 'XZOy-foDMTZvUSbrGDsQjW1v5xYITeQRNME87wa0XFHvcW4VS5LtM5BZ20ivIfTe2jlkYa7yGddow-QbvioeBg',
      type: 'usher'
    }
  ],
  at: '232',
  current_hash: 'NX4EuoFQ2zOzGEZFtdNkPK4/d8Ri4Wefiyv2GBCfI1M='
}
```
