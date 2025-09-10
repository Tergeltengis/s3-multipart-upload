## Performance Results

✅ **Speed Improvement:** 3× faster with multipart upload compared to single upload.

---

### File Size Tested

<br/>
<img width="400" height="50" alt="image" src="https://github.com/user-attachments/assets/9767de9f-f31b-4b91-8531-7cf6a74454b8" />

---

### Single Upload

- **Total time:** 46 seconds  
- Performance is limited because the entire file uploads as a single chunk.

<img width="1115" height="192" alt="image" src="https://github.com/user-attachments/assets/ae6b7710-1175-48b5-b462-e97220429986" />

---

### Multipart Upload

- **Longest part:** 15 seconds  
- Upload is split into multiple chunks, allowing parallel uploads and faster overall performance.

<img width="734" height="254" alt="image" src="https://github.com/user-attachments/assets/207a0e99-1682-4dce-bca3-ce98061e583d" />

---

### Summary

- Multipart upload significantly reduces the time required for large files.  
- Parallelizing chunks leads to faster and more reliable uploads.
