-- Create Vaccination Clinic 3 table
CREATE TABLE clinic3_data (
PatID VARCHAR(20) PRIMARY KEY,
AGE INT,
PTSEX CHAR(1),
RACETHCODE VARCHAR(50),
ZIPCODE VARCHAR(10),
VaccClass INT,
DATE_OF_VA DATE
);
 
-- Insert sample data for Clinic 3
INSERT INTO clinic3_data (PatID, AGE, PTSEX, RACETHCODE, ZIPCODE, VaccClass, DATE_OF_VA) VALUES
