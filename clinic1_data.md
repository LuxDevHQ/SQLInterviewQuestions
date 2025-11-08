CREATE TABLE clinic1_data (
PatientID VARCHAR(20) PRIMARY KEY,
PatientAge INT,
PatientSex CHAR(1),
RACE_ETH VARCHAR(50),
PatientZIP VARCHAR(10),
VaccineType INT,
VaccDate DATE
);
 
-- Insert sample data for Clinic 1
INSERT INTO clinic1_data (PatientID, PatientAge, PatientSex, RACE_ETH, PatientZIP, VaccineType, VaccDate) VALUES
('20182749', 28, 'F', 'WHITE', '02118', 3, '2024-03-01'),
('22837162', 56, 'M', 'BLACK', '02119', 4, '2024-03-01'),
('22832861', 58, 'M', 'BLACK', '02110', 4, '2024-03-01');
 
('A83719DH', 28, 'F', 'WHITE', '02118', 2, '2023-11-24'),
('B1DBSJFQ', 56, 'M', 'BLACK', '02119', 2, '2023-11-24'),
('FXV9281X', 58, 'M', 'BLACK', '02110', 3, '2023-11-24');
